github URL : https://github.com/sssh311318/ESL_HW4

# Implementation
把platform的filter更改成gaussian的參數，將MASK_N更改成 1 ，然後將輸出圖檔的INDEX更改完之後，輸出的圖片位置就正常了，原本是順時針轉90度。

# Result

## Without DMA

![sim](https://github.com/sssh311318/ESL_HW4/blob/main/DMA_SIM.png?raw=true)

![result](https://github.com/sssh311318/ESL_HW4/blob/main/DMA_RESULT.png?raw=true)

## With DMA)(memcpy)

![DMA](https://github.com/sssh311318/ESL_HW4/blob/main/WO_DMA.png?raw=true)

![RESULT](https://github.com/sssh311318/ESL_HW4/blob/main/WO_DMA_RESULT.png?raw=true)

# Discussions and conclusions.
從上面的結果可以得出，選擇DMA mode的話 instruction的數量和simulated time都是比較小的。

