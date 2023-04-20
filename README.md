## Senior IS Software Components: Ussama Mustafa

### File Overview

The folder contains the following documents:

__Training.ipynb__: This is the file used for transfer learning a text generator. In order to run the file, simply find a preferred dataset, load it into the notebook in the specified cell, then run the entire program. Once training is done, you can save the resulting model in the specified cell. The fine-tuned model can then be used for text generation in the Text_Gen notebook.

__Text_Gen.ipynb__: This is the file used for text generation. It can be used either by loading a pre-trained model, or by loading a fine-tuned model. It is important to note that loading the correct tokenizer plays a big role in the model's performance.

__Art_Gen.ipynb__: This is the file used for art generation through VQGAN+CLIP. In order to use it, users can simply input a text prompt and run the entire notebook. Additional modifications can be made such as changing the shape, quality of the image, or the choice of pre-trained models to download.

__Fast_Art_Gen.ipynb__: Thie is the file used for faster art generation through stable diffusion model. In order to use it, simply run the entire file and use the resulting Gradio Interface. You might have to run the Pyrebase cell twice.

__IS.html__: This is the the file containing the user interface. In order to use it, users can run Fast_Art_Gen.ipynb and copy the URL of the Gradio interface, then paste it into the "src" for the Art Generation iframe.

__styles.css__: This is the file containing the styling for the user interface.

__story_model.pt__: This is a fine-tuned model obtained the training notebook. It can be used for text generation.

