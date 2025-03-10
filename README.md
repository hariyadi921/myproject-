# Clone repo
git clone https://github.com/theox443/myproject
cd myproject

# Build dan test
make all

# Jalankan program Go
./bin/main

# Jalankan skrip Python
python3 scripts/python/data_processor.py
pip freeze > requirements.txt
chmod +x scripts/bash/build.sh
go mod init github.com/theox443/myproject
