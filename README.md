# GenAI Chatbot (google/gemma-2-2b-it)

## Project Overview

This project is a **GenAI Chatbot** built using the **google/gemma-2-2b-it** language model from Google. The chatbot leverages the power of advanced natural language processing (NLP) to generate human-like responses to user input. The project includes a Gradio-based interface that allows users to interact with the chatbot easily in a conversational manner.

The chatbot utilizes the **google/gemma-2-2b-it model**, which is a large-scale language model fine-tuned for tasks like dialogue generation, content completion, and more. 

## google/gemma-2-2b-it Model

The **google/gemma-2-2b-it** model is a powerful causal language model trained on diverse text data. It can generate contextually relevant, coherent, and meaningful responses based on user input. This model is part of Google's Gemma model family, designed to provide high-quality natural language generation capabilities.

You can find more about the model on the [Hugging Face page](https://huggingface.co/google/gemma-2-2b-it).

## Project Screenshots

### Interface

Here’s how the chatbot interface looks:

![Screenshot_Interface](Screenshot_Interface.png)

### Chat Example

Here’s an example of a conversation with the chatbot:

![Screenshot_Chats](Screenshot_Chats.png)

## How to Run the Application

You can run this application in **Google Colab** using a GPU for fast inference.

### Steps:

1. **Download the notebook**:  
   Download the `Chatbot_using_Gemma_2_2B.ipynb` file from this repository.

2. **Upload to Google Colab**:  
   Open the notebook in **Google Colab** by navigating to [Google Colab](https://colab.research.google.com/), and upload the `.ipynb` file.

3. **Install dependencies**:  
   The notebook installs the required dependencies like `gradio` and `transformers` using pip.

4. **Run the cells**:  
   Execute each cell in the notebook sequentially. The last step will launch the Gradio-based chatbot interface.

5. **Access the app**:  
   Once the app is running, you can interact with the chatbot in the provided Gradio interface.

### Requirements

- **Google Colab** or a similar Jupyter notebook environment.
- A **GPU** (optional, but recommended for faster processing).
- **Hugging Face Token**: Make sure to replace the token in the code with your own Hugging Face token.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Now the README reflects the correct model name. Let me know if you need further adjustments!
