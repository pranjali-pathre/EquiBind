# EquiBind

docker build -t container -f Dockerfile .
docker run -v /home/pranjali/dddd:/opt/data/to_predict container python inference.py --config=configs_clean/inference.yml
