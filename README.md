# Run TorchChat in Google Colab with Ngrok

![](https://storage.googleapis.com/mle-courses-prod/users/61b6fa1ba83a7e37c8309756/private-files/c19ab080-4ef1-11ef-a9c5-539ef4fa11ba-Thie__t_ke___chu_a_co__te_n__1_.png)

Original repository: [TorchChat](https://github.com/pytorch/torchchat)

# How to run

1. Open [this Colab](https://colab.research.google.com/drive/1v0lWXIH4lWQAVrP3yNPhEe1r-fv6wZXE?usp=sharing).
2. Run all cells and get the Ngrok link. The link should look like this:
   
   ```
   http://<ngrok-link>
   ```

3. Add this link to [the file](https://github.com/bangoc123/protonx-ai-app-UI/blob/main/src/apiCalls/ai-demos/postQuestionsApiCall.ts) of the client app.

![](https://storage.googleapis.com/mle-courses-prod/users/61b6fa1ba83a7e37c8309756/private-files/8596eb80-4ef1-11ef-a9c5-539ef4fa11ba-Screen_Shot_2024_07_31_at_11.01.06.png)

4. Run the client at port 5000.

![](https://storage.googleapis.com/mle-courses-prod/users/61b6fa1ba83a7e37c8309756/private-files/4352f610-4ef1-11ef-bf69-71eafa46c86b-Screen_Shot_2024_07_31_at_10.59.06.png)