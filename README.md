# HHA504_assignment_ai

## GCP Speech-to-Text
![storage-audio](https://github.com/user-attachments/assets/7617bfdb-dfb0-4ff7-8e10-91127a2aa771)

- The assignment required transcribing a sample audio file using the pre-trained speech model. The first step included the creation of a cloud storage bucket to upload the sample audio file. Next, to make sure that I did not run into any errors when using the Sample Notebook, I clicked on the bucket and went to the permissions section. Under the permissions section, it is important to ensure that public access is enabled, which allows for setting the configurations for granting access. When clicking grant access, set allUsers for New Principals and Storage Object Viewer for Role.
  
![audio-connect](https://github.com/user-attachments/assets/49ad1d16-dc0f-4f2e-ac22-53b2e9302aec)

![audio-transcription](https://github.com/user-attachments/assets/da75024b-d4fd-42d5-90a2-40d689aea676)

- To transcribe the uploaded sample audio file using the pre-trained speech model, I navigated to Vertex AI and chose Colab Enterprise under Notebooks. I selected the "Getting started with Gemini 1.5 Flash" under the Sample Notebooks section. After opening the Sample Notebook, I ran the default code for the installing, initializing, and loading of Vertex AI SDK and Gemini 1.5 Flash Model. Then, for Audio Understanding, I replaced the default code to define my bucket and audio file name as well as ensured that it was reflected for the audio file URI and URL. After running the code under Audio Understanding, I replaced the prompt under Example 2: Transcription, which then returned the text of my audio file upon running the code.

## GCP Vision API
![storage-image](https://github.com/user-attachments/assets/7617bfdb-dfb0-4ff7-8e10-91127a2aa771)

- The assignment required uploading a sample image file for object detection using the pre-configured sample notebook. I uploaded the sample image file to the same cloud storage bucket created at the beginning of the assignment used for the speech-to-text portion. It is important to leave the settings under permissions as the same configurations.
  
![image-connect](https://github.com/user-attachments/assets/5869360b-21f6-41a0-8771-fd7efbadbd74)

![image-detection](https://github.com/user-attachments/assets/89070e47-1cba-49ad-8951-bdb66f1a4ebe)

- In the same notebook used for the speech-to-text portion of the assignment, I navigated to the section All Modalities at once section to use the Vision API. I removed any line of code relating to video files. Then, similar to the sample audio file, I started by replacing the default code to define my bucket and image file name as well as ensured that it was reflected for the image file URI and URL. In the code space below, I replaced the prompt to better suit the assignment directions of object detection for the image. After running the code, it explained what was happening in the image and listed the objects in the image with a description.

## Azure AI Vision


## Reflection/Comparison/Challenges 
