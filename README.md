

```markdown
# Transformer-Based Text Generator

This project implements a Transformer-based language model using Keras and TensorFlow. It learns to predict the next word in a sentence using the IMDb movie reviews dataset.

## 🚀 Features

- Custom Transformer Block with multi-head attention
- Positional and token embeddings
- Custom causal attention masking for autoregressive behavior
- Text vectorization and standardization
- Callback for live text generation during training
- Trained on IMDB reviews dataset (positive & negative)

## 🧠 Model Architecture

- **Embedding Layer**: Token + Position embeddings
- **Transformer Block**: Multi-head attention and feed-forward layers
- **Output Layer**: Dense layer with vocabulary-sized logits

## 📁 Dataset Structure

Make sure the following IMDb dataset folders are downloaded and extracted in the root directory:
```

aclImdb/
├── train/
│   ├── pos/
│   └── neg/
├── test/
│   ├── pos/
│   └── neg/

````

## 🛠️ Installation

```bash
pip install tensorflow keras numpy
````

## 🏃‍♂️ Run the Model

```python
python your_script.py
```

Make sure to adjust the script filename if necessary.

## 📝 Text Generation

The model generates text based on a prompt at the end of each epoch. For example:

**Prompt**: `"this movie is"`

**Generated**:

```
this movie is a great film that captures the heart and soul of its characters beautifully.
```

## 🔧 Hyperparameters

* `vocab_size = 20000`
* `maxlen = 80`
* `embed_dim = 256`
* `num_heads = 2`
* `feed_forward_dim = 256`
* `batch_size = 128`
* `epochs = 25`

## 🙌 Credits

Developed using:

* TensorFlow
* Keras
* IMDb Dataset

---



```

```
