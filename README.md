# nlpcompetition
final model

## Usage
```
hidden_size = 512
net = NMT(hidden_size, hindi_tokenizer, eng_tokenizer, dataloader) # class defined in notebook
net.load_state_dict(torch.load("vattentiondictfinalv1.ckpt"))
```
