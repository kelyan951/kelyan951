!pip install pygit2==1.12.2
%cd /content
!git clone https://github.com/IIIyasviel/Fooocus.git

%cd /content/Foocus/models/uspcale models/
!wget -0 foocus_upscaler_s409985e.bin https://huggingface.co/LLLyasvviel/misc/resolve/main/foocus_upscaler_s409985e5.bin?download=true

%cd /content/Fooocus
!python entry_with_update.py --share
