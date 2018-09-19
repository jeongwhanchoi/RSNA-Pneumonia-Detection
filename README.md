# RSNA Pneumonia Detection

But the title **Pneumonia Detection** for the competition is misleading beacuse you actually have to do **Lung Opacities Detection**, and lung opacities are not the same as penumonia. Lung opacities are vague, fuzzy cloud of white in the darkness of the lungs, which makes detecting them a real challenge.

## Normal Images

What does a nomral image liik like?

### Chest Radiographs Basics

#### X-ray

X-ray passes through the body and reaches a detector on the other side. Tissues with sparse material, such as lungs which are full of air, do not absorb the X-rays and appear black in the image. Dense tissues such as bones absorb the X-rays and appear white in the image. In short:

- Black = Air
- White = Bone
- Grey = Tissue or Fluid

## Lung Opacity

### The Difinition of Opacity

#### Opacity

> *"Opacity refers to any area that preferentially attentuates the x-ray beam and therefore appears more opaque than the surrounding area. It is a nonspecific term that does not indicate the size or pathologic nature of the abnormality."* 
>
> *from Felson's Principles of Chest Roentgenology*

### What are opacities and what can we understand if we see them?

Usually the lungs are full of air. When someone **pneumonia**, the air in the lungs is replaced by other material – fluids, bacteria, immune system cells, etc. That's why areas of opcities are areas that are grey but should be more black. When we see them we understand that the lung tissue in that area is probably not healthy.