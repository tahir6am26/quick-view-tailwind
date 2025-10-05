<script setup>
import { Accordion, AccordionContent, AccordionItem, AccordionTrigger } from '@/components/ui/accordion'
</script>

<template>
    <div class="w-[1024px] mx-auto my-10 overflow-hidden">
      <Accordion type="single" collapsible class="grid gap-4" :default-value="'item-1'">
        <AccordionItem value="item-1" class="group hover:bg-gray-200 bg-gray-100 border-0 duration-200 rounded-lg py-0 px-4 data-[state=open]:bg-gray-200">
          <AccordionTrigger class="hover:no-underline hover:cursor-pointer">Is it accessible?</AccordionTrigger>
          <AccordionContent>
            Yes. It adheres to the WAI-ARIA design pattern.
          </AccordionContent>
        </AccordionItem>
        <AccordionItem value="item-2" class="group hover:bg-gray-200 bg-gray-100 border-0 duration-200 rounded-lg py-0 px-4 data-[state=open]:bg-gray-200">
          <AccordionTrigger class="hover:no-underline hover:cursor-pointer">Coast Of part</AccordionTrigger>
          <AccordionContent>
            Trading enabled.
          </AccordionContent>
        </AccordionItem>
        <AccordionItem value="item-3" class="group hover:bg-gray-200 bg-gray-100 border-0 duration-200 rounded-lg py-0 px-4 data-[state=open]:bg-gray-200">
          <AccordionTrigger class="hover:no-underline hover:cursor-pointer">Swing of none</AccordionTrigger>
          <AccordionContent>
            Yes. It adheres to the WAI-ARIA design pattern.
          </AccordionContent>
        </AccordionItem>
        <AccordionItem value="item-4" class="group hover:bg-gray-200 bg-gray-100 border-0 duration-200 rounded-lg py-0 px-4 data-[state=open]:bg-gray-200">
          <AccordionTrigger class="hover:no-underline hover:cursor-pointer">Carebian coast</AccordionTrigger>
          <AccordionContent>
            Yes. It adheres to the WAI-ARIA design pattern.
          </AccordionContent>
        </AccordionItem>
        <AccordionItem value="item-5" class="group hover:bg-gray-200 bg-gray-100 border-0 duration-200 rounded-lg py-0 px-4 data-[state=open]:bg-gray-200">
          <AccordionTrigger class="hover:no-underline hover:cursor-pointer">impact organic</AccordionTrigger>
          <AccordionContent>
            Yes. It adheres to the WAI-ARIA design pattern.
          </AccordionContent>
        </AccordionItem>
      </Accordion>
    </div>
</template>

<style scoped>

</style>