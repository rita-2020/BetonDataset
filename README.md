**GAN to Concrete**

This is the pretrained model for  _Béton_, along with its raw image dataset. The model uses -deep learning- through pix2pix, a conditional generative adversarial network autoencoder.

![Screen_Shot_2020-06-20_at_12.46.31_PM](/uploads/318bd9915bff47bd174eeb558b6e0a0c/Screen_Shot_2020-06-20_at_12.46.31_PM.png)![IMG_1_copy](/uploads/d025c0252ed28fffb9d672a66552c5b4/IMG_1_copy.png)

# Overview 
A collection of photographs showing found Béton have been stored in a dedicated image dataset. With this dataset, I am exploring ways that _‘Machine Learners’_ refers to humans as much as it does to computers. As a single _‘variable’_ which represents experimentation and fragmentation, _Béton_ can be computationally seen within the ‘Latent Space.’ In this hidden layer of machine learning, input data is broken down and apart, and tries to re-assemble itself by learning possible compositions. While the results are ambiguous, unsupervised learning does help understand, and predict unknown data better.

To visualize the latent space, I feed my image dataset of _Béton_ to a network that de-codes this inner process and generates the re-done _Béton_ back into concrete. 

**[Click here](http://igor.gold.ac.uk/~rhadd001/GANtoBeton/) to see a simulated display for an exhibition.** 
Projection of a photo-grid on an entire wall surface.The photo-grid shuffles through the entire training data, and the predictions of the trained model.
The Beton sculptures would be displayed physically either on the floor or on plinths.



Project Adjustments to Covid-19 lockdown, and Lebanese Economic/Political/Social Unrest i.e. electricity cuts:

**From Automation to Collaboration :**
Initially, I wanted to build my own network model which would compute the whole process of data input into latent sculpture. The output of the model would have been a step further from a reconstructed visualization as .JPG into an .STL file. The .STL file is a 3D render which is recognized by 3D printers. I was beginning to look into point clouds to automate this process through my model. And finally the .STL would have been rendered to concrete through a 3Dprinter. 
I did not carry on to explore Tensorflow and configure my own GAN, but rather I trained my own model through pix2pix which has its’ pre-set properties. Using my knowledge of python from previous MachineLearning modules. With adjustment, I remained with my Data Input to physical Output idea. Instead of 3D printing a GAN into concrete, I went to a brick factory  and molded a Beton myself following the meticulous designs generated by my model. The concept idea of rendering a neural network to concrete remains as intended, however the process of scultping myself involves more collaboration with the network, rather than giving the project full automation. 
# Data
![Screen_Shot_2020-06-20_at_10.33.26_PM](/uploads/0fb2606a2fe26eb1e8ebe275e8e33cd2/Screen_Shot_2020-06-20_at_10.33.26_PM.png)

The Beton Dataset is a collection of self-taken photos of beton spontaneously found throughout the city of Beirut and its outskirts. 

Scraping images from large online databases is the conventional way to collect images to work with GANS. Deep learning goes hand in hand with big data, as it deals with extracting meaningful information from a vast amount of information. Memo Aktins Deep Mediations illustrates GAN’s as a powerful medium for creative expression. Where his image dataset consist of ‘everything’. All scraped from Flickr with tags such as ‘life, love, faith, everything, etc.’. 
The power of GANs to learn the distribution of all of its input data,  and to find forms, compositions, and patterns within its endless network of possible trajectories makes it a fascinating tool to understand big data better, and distinguishes it from other algorithms. 

My raw image dataset currently consists of about only 40 original images. The model however has been trained on a  total of 274 images, consisting of re-sized, cropped, rotated, and transformed adjustments from the original dataset. I then ran a batch process to rescale the images to 256x256. The method used for training is ‘inpainting’ from pix2pix-tensorflow. 
Creating the Beton dataset manually was by choice firstly because data mining is restricted to digitized and transparent information, and the definition I see Beton in falls out of its categorization within construction-sites. The dataset grew as i came across different uses of Beton, and it was never by intention to search for them. I did also receive images by text from others who would come across one. Getting the data was a very material and lived-in process. 

# Latent Variables and _Béton_
“Unsupervised algorithms are used often in an exploratory setting when a data scientist wants to understand the data better, because there is no way to “tell” the algorithm what we are looking for. 

Constraining an autoencoder during training(example:adding noise) pushes it to discover patterns in the data.” 

From Classification algorithms that distribute entities into decision boundaries, to optimization models that maximize the objective function. Information is fed to the machine in hope that it can find relevant features, when however, the network is also demanding features of relevant information. In this case, humans and machines must deal with the same problem. 
In a recent book on Machine Learning titled “Machine Learners” Adrian Mackenzie writes
 > “Who or what is a machine learner? I am focusing on machine learners—a term that refers to both humans and machines or human-machine relations.” 
 
Mackenzie uses the term machine learner to refer to the machine as much as to the learning human. While human-machine collaborations become frequented , Machine Learners perform an accumulation of data, and both make biases. And so the question of how to respond to unexpected situations remains as challenging. When the situation and its entities become un-recognizable, the biases begin to challenge themselves as they must redistribute their ideas within experimentation. The stage of experimentation is crucial in allowing and engaging with for different possibilities. I make analogies to this space through latency in computing, and through the use of Béton in Lebanon. 

The space where the network is learning the distributions of its data is called the Latent Space. Within the latent space, neural nets autoencodes its data into really low resolution, and this low res data becomes the material it uses to interpolate through the form and composition of varying data inputs. In times of necessity, the Béton suddenly comes to life as it becomes re-purposed and re-identified. It fills cracked spaces that only adaptation can mend through. Its necessity cannot come from an optimized objective function, as it has de-routed relevance from another point of interest. It is comparable to a latent variable, broken up and dispersed, as it combines to different forms and compositions when spotted. Unpredicted situations forces set biases to be challenged, and stirs them to find new possibilities. 


# Rendering a Neural Network to Concrete
![Screen_Shot_2020-06-22_at_1.17.51_PM](/uploads/5b6cbad21efdeb77ff5af14469adef32/Screen_Shot_2020-06-22_at_1.17.51_PM.png) 

Visualised reconstructions generated by my model where used as reference to manipulate a concrete slab. 
 
I went to the factory where they make concrete slabs. The factory makes some in bulk every morning and piles them in a row until they dry within a day. To manipulate or mold the concrete smoothly, I had about 5 minutes after it was taken out of the cast before the block would shatter instead of mend. 
The concrete block has a very common shape and use, it is either a perfect block, or it is a bit shattered down or broken. But it is never slightly morphed or bended with smooth curves. The fact that it dries so quickly explained it. The morphed Beton did startle some people who saw it, wondering what it was, or how it came to be. I am excited by this possibility of having a morphed Beton, it certainly does feel uncanny. Without the direction and vision of the GAN I would not have known how to mend the block. It could have easily looked like shattered stone, but the GAN highlighted and emphasized the main features to be manipulated. 




# Acknowledgements 

![IMG_9689_copy_5-inputs](/uploads/6e71f5f390febbecb2a9ad4e1e44f07c/IMG_9689_copy_5-inputs.png) 
![IMG_9689_copy_5-outputs](/uploads/1994066299fb2a1d6c03d1b52a399f1f/IMG_9689_copy_5-outputs.png) 
![Screen_Shot_2020-06-15_at_10.40.19_PM](/uploads/4d82b64e207f75e7e93442bab5d932cb/Screen_Shot_2020-06-15_at_10.40.19_PM.png)