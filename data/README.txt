1. Simulation
morocco.jpg: A clear, high-resolution image of a Moroccan license plate used as the primary ground truth for motion blur simulations. -> https://licenseplatemania.com/landenvolledig/marokko/marokko_6.jpg
moroccoo.jpg: A secondary sharp reference image of a Moroccan license plate. ->  https://www.europlates.eu/images/plates/ma/P02026.JPG
jeep.jpg: A real-world capture of an SUV license plate -> https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDGuCnnKQ5ZNfiTJ4zuEtAA0OunEgW3GxAAg&s

2. Real-World Test Data
green_car.jpg: A real-world capture of an Audi suffering from significant defocus blur (out-of-focus) -> https://blog.ampedsoftware.com/wp-content/uploads/2023/10/image7-1.jpg  //CROP : cropped_plate = real_image_full[int(h*0.43):int(h*0.64), int(w*0.39):int(w*0.73)]
defocused.jpg: A test case featuring defocus blur. -> https://user-gen-media-assets.s3.amazonaws.com/gemini_images/0b567c18-5a56-4d11-a526-e0b28b735aed.png  //CROP : cropped_plate = real_image_full[int(h*0.30):int(h*0.70), int(w*0.12):int(w*0.88)]
