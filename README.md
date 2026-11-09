# Open Sandbox

Open Sandbox is an app that enables users to run open-source models directly on their own phones, using google colab and their own drive. It is purposefully designed to enable the user complete and total access to their model use, preventing any information from being linked.
The motivation behind this app is because I have noticed people (including my parents) happen to share sensitive information with AI models, perhaps unknowningly. This app will hopefully become a replacement for detailing information about sensitive topics, seeing as the user can fully control their model's memory, usage, and all other aspects, preventing information from being leaked.


Currently, the app is limited to Natural Language Transformers, imported from the huggingface library, but as new updates roll out compatibility with Mac and other models, such as vision generators.

Note that the app may take some time to lead, as the app runs the models (that take time to load) on the host computers that Google Colab provides. Once you press the "Runtime ==> Run All" button, the in-app screen will close once the connection is established with the model.
There is no need to try and close the window earlier.

Below, images of the app are presented. 

# Images

Image of the Start Page (Light Mode):

<img width="260" height="400" alt="sandboxStartPage" src="https://github.com/user-attachments/assets/2d33a07d-948f-43af-9631-b291f2325496" />

Image of the Chat Page (Light Mode):

<img width="260" height="400" alt="sandboxChatPage" src="https://github.com/user-attachments/assets/4024a60c-df4f-4e64-a8b7-fa54befb97e7" />

Image of the Chat Page (Waiting for Response, Light Mode):

<img width="260" height="400" alt="sandboxThinking" src="https://github.com/user-attachments/assets/1f6a3b83-0679-40c3-8398-8fd06d418658" />

# Disclaimer
Note, the models are not owned by me. All models are open sourced, and it is up to the user to make sure that they do not violate the licenses for the model. Furthermore, if the user runs out of compute units, it is up to them to either purchase more or wait for their free compute units to refill. 

The models may take a long time to load, or the models may be too big for the GPU you are trying to load it on. In this case, you need to either change your models or pay Google Colab for the access to more RAM and GPUs.
