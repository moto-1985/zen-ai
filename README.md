https://zenn.dev/ml_bear/books/d1f060a3f166a5/viewer/0e8fe3

環境構築
https://alaki.co.jp/blog/?p=4129
```
brew install pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
pyenv install -l
pyenv install 3.10.12
pip install streamlit
streamlit hello
pip install langchain
```
