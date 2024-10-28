---
title: Llama 3.2 1B GGUF
emoji: 🦙
colorFrom: pink
colorTo: indigo
sdk: gradio
sdk_version: 4.44.1
app_file: app.py
pinned: true
license: creativeml-openrail-m
short_description: Llama-3.2-1B-GGUF
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

# Uploaded  model

- **Developed by:** prithivMLmods
- **License:** apache-2.0
- **Finetuned from model :** unsloth/llama-3.2-1b-instruct-bnb-4bit
---

# Run with Ollama 🦙

### Download and Install Ollama

To get started, download Ollama from [https://ollama.com/download](https://ollama.com/download) and install it on your Windows or Mac system.

### Run Your Own Model in Minutes

### Steps to Run GGUF Models:

#### 1. Create the Model File
   - Name your model file appropriately, for example, `metallama`.

#### 2. Add the Template Command
   - Include a `FROM` line with the base model file. For instance:

     ```bash
     FROM Llama-3.2-1B.F16.gguf
     ```

   - Make sure the model file is in the same directory as your script.

#### 3. Create and Patch the Model
   - Use the following command in your terminal to create and patch your model:

     ```bash
     ollama create metallama -f ./metallama
     ```

   - Upon success, a confirmation message will appear.

   - To verify that the model was created successfully, run:

     ```bash
     ollama list
     ```

     Ensure that `metallama` appears in the list of models.

---

## Running the Model

To run the model, use:

```bash
ollama run metallama
```

### Sample Usage

In the command prompt, run:

```bash
D:\>ollama run metallama
```

Example interaction:

```plaintext
>>> write a mini passage about space x
Space X, the private aerospace company founded by Elon Musk, is revolutionizing the field of space exploration.
With its ambitious goals to make humanity a multi-planetary species and establish a sustainable human presence in
the cosmos, Space X has become a leading player in the industry. The company's spacecraft, like the Falcon 9, have
demonstrated remarkable capabilities, allowing for the transport of crews and cargo into space with unprecedented
efficiency. As technology continues to advance, the possibility of establishing permanent colonies on Mars becomes
increasingly feasible, thanks in part to the success of reusable rockets that can launch multiple times without
sustaining significant damage. The journey towards becoming a multi-planetary species is underway, and Space X
plays a pivotal role in pushing the boundaries of human exploration and settlement.
```

---

# Llama-3.2-1B-GGUF

![Demo of Project]([Demo/gguf.gif](https://huggingface.co/prithivMLmods/Llama-3.2-1B-GGUF/resolve/main/Demo/gguf.gif))



You’re now ready to run your own model with Ollama!

🦙 - https://youtu.be/_9IcVFuql2s?si=0NjKlJ1GDCmuJHvQ
