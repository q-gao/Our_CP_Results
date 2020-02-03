# Comparison of Our Handheld Very Low Light Results to the Great Google Night Sight

-	`*_NightSight.jpg` and `*_Ours.jpg` are Google’s and ours results, respectively
-	Most scenes have less than 1 lux brightness. Some have brightness of as low as 0.1 lux
- Our results tend to have less noise and more details than Google’s. In particular, the flat aeas in ours results are very clean.
- The comparison was performed to be as fair as possible
  - The same smartphone running Qualcomm Snapdragon 855 was used.
  - The same ISO and exposure time were used
  - The same number of images were used for each shot
  - 3 shots per scene were taken for each method and the best was chosen for comparison
- The current non-fully-optimized implementation of our algorithm takes around 4 seconds that is comparable to Google Night Sight on Snapdragon 855. We expect further optimization will reduce the running time by around half.
- Note that we fed our denoised RAW images to a Qualcomm ISP to generate the final images that have different white balancing and tone mapping from Google ISP. Please focus on image noise and details. 

