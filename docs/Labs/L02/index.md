
## Print Something Small

### Download 
I chose to print a [hex key holder](https://www.printables.com/model/1818935-hex-key-holder-skadis) which is product that I use a lot for my personal hardware projects. I noted that this is a size-sensitive item and it might be negatively affected by the size stipulations. I was curious to see how different in size the holder would be when scaled down to the requirements. 
<p align="center">
  <img width="500" alt="Hex Key Holder page" src="https://github.com/user-attachments/assets/b340e651-9db6-41ae-99b1-704c6a8cedee"/> 
</p> 

In my search process, I saw some other items I might want to print but did not want to select as others in the class had already picked them. One such item was the [wedge-lock clip](https://www.printables.com/model/1807378-universal-clip-self-tightening) that Dr. Fagan used as an example. 
<p align="center">
  <img width="500"  alt="Wedge Clip Page" src="https://github.com/user-attachments/assets/83f087a6-0bfe-4931-bed6-cdfe937fe11f" /> 
</p> 
 



### Preprocessor
When adding the item to Prusa Slicer, I chose to maintain the original build orientation. This was necessary because there are numbers printed on the top which need to stay on the topmost face. 
The holder was initially 4x1x1 inches so to make the holder fit within the lab parameters, I scaled the Z down to 0.25 inches. This change resulted in the dimensions being 1x0.28x0.25 in.  \
<img width="500" alt="preScale" src="https://github.com/user-attachments/assets/72d381f3-94c3-4bdc-ac28-d2dbf66b98a5" />
<img width="500" alt="postScale" src="https://github.com/user-attachments/assets/2e3dc485-f03b-4d0e-9cf7-30691df5085f" />

Depicted in these images are our print settings and sliced items. There was an estimated 13 minutes of print time.

<p align="center">
  <img width="400"  alt="printSettings" src="https://github.com/user-attachments/assets/7442a6dc-8d4c-4c96-ae80-ddc0d3cc406a" />
  <img width="500"  alt="midSlice" src="https://github.com/user-attachments/assets/7c66e12c-a056-4135-81c7-4bde6d6c4fa1" /> 
</p> 



When we brought our USB loaded with the g-code to the printer, it threw an error saying that the filament in the printer did not match the filament in the code. We are unsure of why this error appeared as we did match our g-code to the PETG in the printer. Regardless, the printer eventually continued in the process. We are unsure of what caused the error, it could have possibly been avoided by choosing one of the other PETG options in Prusa Slicer rather than Generic PETG.




### Print
My printing group was comprised of Jack, Saniyah, and Ethan. We printed on printer PC-13. When we checked the filament type on the side of the printer, we accidentally displaced the wiring. The filament got caught on the housing which prevented it from properly feeding into the printer. Because of this, we had to stop our first print early as it was faulty. Here is the link to a video of the [failed print](https://drive.google.com/file/d/1-ozBOYNmDv479gbap5cH4E-5JWEDc4cd/view?usp=sharing). As shown in the video, the printer stopped laying filament and was overall streaky in its layering. Additionally, the printer arms repeatedly agitated the laid filament, pulling it off of the base.

Our [second print](https://drive.google.com/file/d/1R2oSZ-rygvIJVRcmnrfYyNWbnaZerJ5O/view?usp=sharing) was successful. There were no problems and we were able to collect the items we expected. The print took 18 minutes and 24 seconds.

<img width="500" alt="printTime" src="https://github.com/user-attachments/assets/498ea3e4-8b8b-4901-82c8-3f3b1ed4b77a" />


The image below shows the successful and unsuccessful prints. The unsuccessful print is noticeably shorter as it was stopped early in its printing process. The successful print is near perfect aside from some jumbling of the numbers on the top. I believe this is because the smaller scale made it harder for the printer to leave fine details.

<img width="500" alt="ruler" src="https://github.com/user-attachments/assets/3f30bd96-2b37-429d-a657-87f9464d5f59" />





### Lessons Learned

I chose to print an item that is technically useful but became useless and inaccurate because of the size stipulations. I had to scale the hex key holder down to a much smaller size which resulted in the relevant function not being possible anymore. In the future, I would attempt to find/design an item that is adaptable to the smaller size. Alternatively, I would print something like the hex key holder in its intended size.
My group's first print was not successful, likely due to a problem feeding the filament. As shown, the printer was struggling to lay down material which made the products uneven. The uneven materials were then repeatedly agitated by the printer tip as it moved. Dr. Fagan and Dr. Raquet helped us identify the problem and continue on with a successful print. 
Due to the limited time allotted for printing, groups picked a printer and then developed their g-code to be based on the type of filament already loaded into that printer. My group picked a printer that was prepared with PETG filament. For a future print, I would switch to PLA filament to see if there were any noticeable differences in print time, print quality, or texture.
Heating process

## DfAM

Design for Additive Manufacturing (DfAM) has a few guidelines intended for engineers to maximize their efficiency and functionality. One concept is that of designing for minimal usage. Minimal usage is best when products need lightweight but strong components. A method of minimal usage is topology optimization. This method describes designing a product with built-in holes where material is not needed. Often seen in car design, suspension parts may be hollowed out in places to reduce weight without compromising strength. 

<img width="400" alt="fsae suspension" src="https://github.com/user-attachments/assets/f773aefe-1202-4268-b523-1629b4595687" />

## FDM

Fused Deposition Modeling (FDM) is a low-cost and quick manufacturing technology, and as such, it has some drawbacks. I focused on possible negative effects of overhangs in FDM projects. Overhang warping is a common issue with FDM, resulting from a lack of support at the base. Generally, overhangs can be printed at a 45-degree angle without any adverse effects, as there is a substantial amount of support. At more extreme angles, overhangs can pull apart the product.

I learned from my classmate that FDM is sensitive to heat, and the shape can be negatively affected by using bad materials or by cooling too quickly.

