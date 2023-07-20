Arquivos da implementação de uma API utilizando a ferramenta RAMOSE: https://github.com/opencitations/ramose

Para executar a implementação foi utilizado o atalho /test/test_windows.bat
O comando definido sendo usado foi:

py -m venv "." & Scripts\pip.exe install --upgrade pip & Scripts\pip.exe install -r requirements.txt & Scripts\python -m ramose -s test_data\test.hf -w 127.0.0.1:8080

Esse é executado dentro da pasta test

