# SecretSharing

This describes how to share secrets between two mobile devices using QR codes. The goal is to exchange information without the need of using network, bluetooth, or NFC connections, while an adversary is observing the displays of the devices, e.g., shoulder surfer, surveillance camera.

<img src="https://raw.githubusercontent.com/AppPETs/SecretSharing-Whitepaper/master/figures/mockup%403x.png" height="798px" width="400px" alt="Mockup of the user interface of the demo application."/>

For a demo-application see [SecretSharing-iOS](https://github.com/AppPETs/SecretSharing-iOS).

## Compilation

The article can be compiled using `latexmk`:

```sh
latexmk -pdf -interaction=nonstopmode -f article.tex
```

There are also compiled PDF files in the releases section [[Download PDF](https://github.com/AppPETs/SecretSharing-Whitepaper/releases/download/v1.0.0/article.pdf)].