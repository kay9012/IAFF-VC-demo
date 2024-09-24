---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Abstract

Voice Conversion (VC) must reflect the characteristics of the target speaker while maintaining the content of the source speech. The existing methods pay more attention to extracting more detailed representation instead of integrating different representations, unable to take into account both content and speaker characteristics, causing a trade-off problem between them. In this study, we propose IAFF-VC, which can be applied to non-parallel any-to-any VC, combining an encoder-decoder and an attentional feature fusion block. The proposed EMAFF block can group the channel dimensions into multiple sub-features which makes the spatial semantic features well-distributed inside each feature group to better combine different representations. We evaluated IAFF-VC on the VCTK dataset in terms of the maintenance of the source content, target speaker similarity, and converted naturalness. Experimental results for one-shot VC suggest that IAFF-VC achieves state-of-the-art performance while mitigating the trade-off problem encountered in the existing VC methods.

## Audio examples

> We set two scenarios: seen-to-seen and unseen-to-unseen.
> 
> F means "Female", and M maen "Male".


### Any-to-Any shot

**S2S:**

F-F:

*  source:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/F-F/p234_029_p308_414_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/F-F/p234_029_p308_414_trg_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/F-F/p234_029_p308_414_cnv_gen.wav" type="audio/wav" /></audio>
   
F-M:

*  source:

     <audio controls="controls" preload="none"> <source src="sample/s2s/F-M/p228_274_p279_288_src_gen.wav" type="audio/wav" /></audio>

*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/F-M/p228_274_p279_288_trg_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/F-M/p228_274_p279_288_cnv_gen.wav" type="audio/wav" /></audio> 

M-M:

*  source：

     <audio controls="controls" preload="none"> <source src="sample/s2s/M-M/p252_239_p278_024_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/s2s/M-M/p252_239_p278_024_trg_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/s2s/M-M/p252_239_p278_024_cnv_gen.wav" type="audio/wav" /></audio> 

M-F:

*  source：

      <audio controls="controls" preload="none"> <source src="sample/s2s/M-F/p226_273_p318_024_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
      <audio controls="controls" preload="none"> <source src="sample/s2s/M-F/p226_273_p318_024_trg_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/s2s/M-F/p226_273_p318_024_cnv_gen.wav" type="audio/wav" /></audio> 


**U2U:**

F-F:

*  source:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/F-F/p336_333_p236_382_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/F-F/p336_333_p236_382_trg_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/F-F/p336_333_p236_382_cnv_gen.wav" type="audio/wav" /></audio>
   
F-M:

*  source:

     <audio controls="controls" preload="none"> <source src="sample/u2u/F-M/p336_224_p316_200_src_gen.wav" type="audio/wav" /></audio>

*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/F-M/p336_224_p316_200_trg_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/F-M/p336_224_p316_200_cnv_gen.wav" type="audio/wav" /></audio> 

M-M:

*  source：

     <audio controls="controls" preload="none"> <source src="sample/u2u/M-M/p374_203_p260_274_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/u2u/M-M/p374_203_p260_274_trg_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/u2u/M-M/p374_203_p260_274_cnv_gen.wav" type="audio/wav" /></audio> 

M-F:

*  source：

      <audio controls="controls" preload="none"> <source src="sample/u2u/M-F/p260_315_p336_225_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
      <audio controls="controls" preload="none"> <source src="sample/u2u/M-F/p260_315_p336_225_trg_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/u2u/M-F/p260_315_p336_225_cnv_gen.wav" type="audio/wav" /></audio> 

### Many-to-Many shot

#### uttr=3

**S2S:**

F-F:

*  source:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-F/from_p329_037_to_p280_342_p280_210_p280_305_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-F/from_p329_037_to_p280_342_p280_210_p280_305_trg0_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-F/from_p329_037_to_p280_342_p280_210_p280_305_cnv_gen.wav" type="audio/wav" /></audio>
   
F-M:

*  source:

     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-M/from_s5_025_to_p345_254_p345_174_p345_298_src_gen.wav" type="audio/wav" /></audio>

*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-M/from_s5_025_to_p345_254_p345_174_p345_298_trg0_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/F-M/from_s5_025_to_p345_254_p345_174_p345_298_cnv_gen.wav" type="audio/wav" /></audio> 

M-M:

*  source：

     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/M-M/from_p334_209_to_p364_170_p364_196_p364_290_src_gen.wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/M-M/from_p334_209_to_p364_170_p364_196_p364_290_trg0_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/M-M/from_p334_209_to_p364_170_p364_196_p364_290_cnv_gen.wav" type="audio/wav" /></audio> 

M-F:

*  source：

      <audio controls="controls" preload="none"> <source src="ssample/uttr=3/s2s/M-F/from_p345_254_to_p351_370_p351_258_p351_204_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/M-F/from_p345_254_to_p351_370_p351_258_p351_204_trg0_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/s2s/M-F/from_p345_254_to_p351_370_p351_258_p351_204_cnv_gen.wav" type="audio/wav" /></audio> 


**U2U:**

F-F:

*  source:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-F/from_p343_296_to_p330_157_p330_255_p330_057_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-F/from_p343_296_to_p330_157_p330_255_p330_057_trg0_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-F/from_p343_296_to_p330_157_p330_255_p330_057_cnv_gen.wav" type="audio/wav" /></audio>
   
F-M:

*  source:

     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-M/from_p343_202_to_p245_129_p245_136_p245_322_src_gen.wav" type="audio/wav" /></audio>

*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-M/from_p343_202_to_p245_129_p245_136_p245_322_trg0_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/F-M/from_p343_202_to_p245_129_p245_136_p245_322_cnv_gen.wav" type="audio/wav" /></audio> 

M-M:

*  source：

     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-M/from_p271_250_to_p245_065_p245_173_p245_261_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
     <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-M/from_p271_250_to_p245_065_p245_173_p245_261_trg0_gen.wav" type="audio/wav" /></audio>
   
*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-M/from_p271_250_to_p245_065_p245_173_p245_261_cnv_gen.wav" type="audio/wav" /></audio> 

M-F:

*  source：

      <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-F/from_p285_221_to_p343_277_p343_386_p343_242_src_gen.wav" type="audio/wav" /></audio>
   
*  target:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-F/from_p285_221_to_p343_277_p343_386_p343_242_trg0_gen.wav" type="audio/wav" /></audio> 

*  converted:
  
      <audio controls="controls" preload="none"> <source src="sample/uttr=3/u2u/M-F/from_p285_221_to_p343_277_p343_386_p343_242_cnv_gen.wav" type="audio/wav" /></audio> 



