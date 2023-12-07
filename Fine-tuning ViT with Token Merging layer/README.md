# Fine-tuning ViT with Token Merging Layer on CIFAR-10
Simple fine tuning code on CIFAR-10 for [timm models](https://huggingface.co/timm) with token merging layer applied 


## Dependencies
 - python >= 3.8
 - pytorch >= 1.12.1  # For scatter_reduce
 - torchvision        # With matching version for your pytorch install
 - timm == 0.4.12     # Might work on other versions, but this is what we tested
