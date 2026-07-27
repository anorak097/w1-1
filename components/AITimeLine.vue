<script setup lang="ts">
import { ref, computed } from 'vue'

interface TimelineItem {
    date: string
    title: string
    description: string
    icon?: string
    position: 'top' | 'bottom'
    order: number
}

const props = withDefaults(defineProps<{
    activeIndex?: number 
}>(), {
    activeIndex: 4 
})

const timelineItems = ref<TimelineItem[]>([
    {
        date: '1940',
        title: 'Bombe',
        description: '二戰時期密碼破譯機',
        icon: 'i-lucide-binary',
        position: 'bottom',
        order: 1
    },
    {
        date: '1950',
        title: 'Imitation Game',
        description: '電腦智慧最初的評估標準',
        icon: 'i-lucide-activity',
        position: 'top',
        order: 2
    },
    {
        date: '1956',
        title: 'Dartmouth Project',
        description: '人工智慧一詞誕生',
        icon: 'i-lucide-lightbulb',
        position: 'top',
        order: 3
    },
    {
        date: '1960 ~ 1970',
        title: 'AI Winter',
        description: '人工智慧發展的低潮期',
        icon: 'i-lucide-snowflake',
        position: 'top',
        order: 4
    },
    {
        date: '1980 ~ 2000',
        title: 'AI Spring',
        description: '人工智慧的復興與發展',
        icon: 'i-lucide-sun',
        position: 'top',
        order: 5
    },
    {
        date: '1997',
        title: 'Deep Blue',
        description: '深藍擊敗西洋棋冠軍',
        icon: 'i-lucide-trophy',
        position: 'bottom',
        order: 6
    },
    {
        date: '2016',
        title: 'Line & Discord bot',
        description: '聊天機器人與自動化普及',
        icon: 'i-lucide-message-square',
        position: 'bottom',
        order: 7
    },
    {
        date: '2022',
        title: 'ChatGPT',
        description: '生成式 AI 的全面爆發',
        icon: 'i-lucide-sparkles',
        position: 'bottom',
        order: 8
    }
])
</script>

<template>
    <div class="w-full relative p-4 min-h-[460px] flex flex-col justify-center select-none">
        <div class="absolute left-4 right-4 h-[2px] bg-gray-200 dark:bg-stone-700 top-1/2 -translate-y-1/2 z-0"></div>

        <div class="w-full grid grid-cols-8 gap-4 relative z-10 grid-rows-2">
            <div 
                v-for="item in timelineItems" 
                :key="item.date" 
                class="relative flex flex-col min-h-[160px]"
                :class="[
                    item.position === 'top' ? 'row-start-1 justify-end pb-6' : 'row-start-2 justify-start pt-6'
                ]"
                :style="{ gridColumnStart: item.order }"
            >
                <div
                    :class="[
                        item.position === 'top'
                            ? 'absolute bottom-0 left-0 translate-y-1/2'
                            : 'absolute top-0 left-0 -translate-y-1/2',
                        'p-1.5 rounded-full text-xs transition-all duration-300 ring-4 ring-white dark:ring-stone-900 z-20',
                        item.order <= props.activeIndex
                            ? 'bg-cyan-500 text-white scale-110 shadow-lg shadow-cyan-500/20'
                            : 'bg-gray-100 dark:bg-stone-800 text-gray-400 dark:text-stone-500'
                    ]"
                >
                    <div :class="item.icon" class="w-4 h-4"></div>
                </div>

                <div :class="[item.position === 'top' ? 'pb-4' : 'pt-4']">
                    <div 
                        class="text-xs font-mono transition-colors duration-300"
                        :class="[item.order <= props.activeIndex ? 'text-cyan-500 dark:text-cyan-400' : 'text-gray-400 dark:text-stone-500']"
                    >
                        {{ item.date }}
                    </div>
                    <div 
                        class="font-bold text-sm mt-0.5 transition-colors duration-300 leading-snug"
                        :class="[item.order <= props.activeIndex ? 'text-stone-900 dark:text-stone-100' : 'text-gray-400 dark:text-stone-500']"
                    >
                        {{ item.title }}
                    </div>
                    <div 
                        class="text-[11px] mt-0.5 break-words transition-colors duration-300 leading-tight"
                        :class="[item.order <= props.activeIndex ? 'text-stone-600 dark:text-stone-300' : 'text-gray-400 dark:text-stone-500']"
                    >
                        {{ item.description }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>