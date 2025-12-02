FROM paradigmi/paradigmi:latest

RUN apt-get update && apt-get install -y \
    pandoc \
    texlive-latex-base \
    texlive-xetex \
    texlive-fonts-recommended \
 && rm -rf /var/lib/apt/lists/*

RUN pip install "nbconvert[webpdf]" && pyppeteer-install