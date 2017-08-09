Link: https://arxiv.org/abs/1706.05137

Title: One Model To Learn Them All

Notes:
- MultiModel is a single model to model tasks from multiple different domains (language, speech, images, etc). It has achieved good results (not state of the art but not shabby)
- Given a model designed for a problem domain, adding another unrelated model not for this domain in general does not hurt model performance. The result is generally on par or improvement. Transfer learning is likely to play a role here
  - Q: The paper argues that there is a degree of transfer learning here, but how can we tell if this is not due to just having significantly more parameters and neurons just somehow help, and that the help is marginal? i.e. you added an "ImageNet" worth of model computation, of course it should help in general
- Attention mechanism (language), separable convolution (image, from Xception net), sparsely gated mixture of experts (language)

TODOs:
- Transfer learning. Read more to that.
- Read more to the techniques used.
