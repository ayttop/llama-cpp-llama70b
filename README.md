# llama-cpp-llama70b




https://colab.research.google.com/drive/1VaL30PmB2DS6oAq6WI_IQvjNRKFR3GZ0?authuser=0#scrollTo=1h0gPgl3Ybu2&uniqifier=1




llama-b3472-bin-win-openblas-x64

!git clone https://github.com/ggerganov/llama.cpp.git
%cd llama.cpp

!make


pip install -r requirements.txt


!./llama-cli -m /content/Meta-Llama-3.1-70B-Instruct-IQ1_M.gguf -t 6 -p "The meaning of life" -c 128



for dialogue
!./llama-cli -m /content/Meta-Llama-3.1-70B-Instruct-IQ1_M.gguf -p "You are a helpful assistant" -cnv -c 128










