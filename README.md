# Samsung-Prism-2024
This is the first trial of the implementation of CLIP (Contrastive Learning Image Pre-Training)

<img width="1470" alt="Screenshot 2024-07-10 at 8 30 15 PM" src="https://github.com/abeersethia/Samsung-Prism-2024/assets/122032191/749d0616-c7d7-4935-8b3a-3905ee92fdeb">

We normalize the features and calculate the dot product of each pair.
This is done by calculating the cosine similarity in the form of a heatmap.

<img width="738" alt="Screenshot 2024-07-10 at 8 32 02 PM" src="https://github.com/abeersethia/Samsung-Prism-2024/assets/122032191/17ac1d5f-f9fa-4887-b59a-a227cb0a101a">

We then tested the results using Zero Shot Image Classification
You can classify images using the cosine similarity (times 100) as the logits to the softmax operation.

<img width="640" alt="Screenshot 2024-07-10 at 8 32 18 PM" src="https://github.com/abeersethia/Samsung-Prism-2024/assets/122032191/96cebd61-df16-4357-a683-73891e0abe09">

This was just a trial run to see the implementation of CLIP.
