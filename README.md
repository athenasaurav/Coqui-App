# Coqui-App

This App will run the Coqui Miltingual Voice Cloning Models(with pre trained weights) either as a flask app or you can run the ipynb file.

Remember to download the models ```SE_checkpoint.pth.tar``` and ```best_model_latest.pth.tar``` and save it some place.

Here are the download links for them
```
SE_checkpoint.pth.tar = "https://huggingface.co/spaces/BilalSardar/Voice-Cloning/resolve/main/SE_checkpoint.pth.tar"
best_model_latest.pth.tar = "https://huggingface.co/spaces/BilalSardar/Voice-Cloning/resolve/main/best_model_latest.pth.tar"
```

Use wget to download. In the [Colab NoteBook](https://github.com/athenasaurav/Coqui-App/blob/main/Coqui_notebook.ipynb) i have pre downloaded it to my Drive and just copyied to my Notebook.


## APP.py

There are three kinds of run env in the repo. The *.ipynb file can be run directly in a colab notebook after downloading the ```SE_checkpoint.pth.tar``` and ```best_model_latest.pth.tar``` in the notebook properly.

You can also run the app.py to launch the Gradio app. Remember to install the necessary dependencies.
