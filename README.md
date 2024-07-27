
# Visual Question Answering with ViLT

This repository contains code for a Visual Question Answering (VQA) system using the ViLT (Vision-and-Language Transformer) model. The system allows you to upload an image and ask questions about its content, providing answers based on the pre-trained ViLT model fine-tuned for VQA.

## Requirements

Ensure you have the following libraries installed:

- `transformers`
- `datasets`
- `torch`
- `torchvision`
- `pillow`

You can install these libraries using the following command:

```bash
pip install transformers datasets torch torchvision pillow
```


## Example

1. Run the script in a Jupyter Notebook or Google Colab.
2. Upload an image when prompted.
3. Enter a question about the uploaded image.
4. The system will output the answer based on the content of the image.

## Notes

- The model used in this example is "dandelin/vilt-b32-finetuned-vqa" from the Hugging Face Model Hub.
- Ensure you have a stable internet connection to download the model and processor when running the code for the first time.
- The performance of the VQA system depends on the quality of the uploaded image and the complexity of the question asked.

## References

- [ViLT: Vision-and-Language Transformer](https://arxiv.org/abs/2102.03334)
- [Hugging Face Transformers](https://github.com/huggingface/transformers)
