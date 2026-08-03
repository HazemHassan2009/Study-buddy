# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.# Study Buddy Chatbot

This project implements a **Study Buddy Chatbot** designed to help school students, particularly toddlers in grade one, with their homework and learning. The chatbot is built using the `Qwen/Qwen2.5-1.5B-Instruct` model and provides an interactive graphical user interface (GUI) powered by Gradio.

## Features

*   **Homework Helper**: Assists students with school-related questions.
*   **Encouraging Tone**: Communicates in a patient, positive, and fun manner suitable for young learners.
*   **Simple English**: Uses easy-to-understand language.
*   **Hint-Based Learning**: Provides hints instead of direct answers to encourage problem-solving.
*   **Scope-Limited**: Strictly focuses on academic topics; will gracefully refuse to answer unrelated questions.
*   **Interactive GUI**: Easy-to-use chat interface built with Gradio.
*   **Kid-Friendly Design**: Colorful and visually appealing layout with a light gray background, playful user message bubbles, and clean, white bot message bubbles with soft edges for a clean look.

## Getting Started

To run this chatbot, you'll need a Google Colab environment with GPU access (recommended).

### Prerequisites

*   Google Colab (or a local Python environment with Jupyter support)
*   Python 3.8+

### Installation

1.  **Open the Notebook in Colab**: If you have the `.ipynb` file, upload it to Google Colab.
2.  **Install Dependencies**: Run the first few cells in the notebook to install necessary libraries like `transformers`, `torch`, and `gradio`.

    ```python
    # Install required libraries
    %pip install torch transformers gradio
    ```

3.  **Load Model and Tokenizer**: The notebook will then load the `Qwen/Qwen2.5-1.5B-Instruct` model and its tokenizer.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer
    # ... (rest of the model loading code)
    ```

## How to Use

Once all the cells are executed, the Gradio interface will launch, providing a web link. Click on this link to interact with your Study Buddy Chatbot.

1.  **Enter your question**: Type your school-related question in the textbox at the bottom of the chat interface.
2.  **Receive help**: The chatbot will respond with encouraging hints to guide you through your learning.

### Example Interaction

*   **User**: "how to add numbers"
*   **Chatbot**: "Okay! Adding numbers is easy. First, let's line up your numbers by their place values..."

## Customization

You can modify the `system_message` variable in the notebook to change the chatbot's role, style, personality, or scope. For example, you could adjust it for different age groups or subjects. The Gradio interface's visual styling can be further customized by editing the `custom_css` variable within the notebook.
