# Assignment images

`q1_portrait.jpg` is extracted directly from the embedded image on page 1 of
`en3160_assignment_01.pdf`, dated September 2, 2026. It is Figure 1b: an 8-bit
grayscale image with width 720 and height 810. The embedded JPEG bytes are
preserved; no page screenshot or image resampling is used.

`q2_brain_pd.png` matches the embedded Figure 2 image on page 2 of the same
assignment PDF pixel for pixel. It has width 181 and height 217 and is stored
as RGB. The notebook loads it as 8-bit grayscale for the intensity
transformations. No screenshot, resizing, or spatial filtering is used to
produce the input image.

`q3_gamma_photo.jpg` is extracted directly from the embedded Figure 3 image
on page 2 of the assignment PDF. It is a 720 x 480 RGB JPEG, with the embedded
JPEG bytes preserved. The notebook reads it in OpenCV's BGR order and converts
it to RGB for display and floating-point Lab for gamma correction.

The source assignment PDF was supplied separately and is not included in this
repository.

A matching separately supplied assignment image archive has not been located.
The embedded images are used for the current Question 1-3 experiments, but
have not been verified as byte-identical to independently supplied originals.
Question 8 will need the specified two original images and their two smaller
versions. Do not substitute screenshots for those evaluation inputs.
