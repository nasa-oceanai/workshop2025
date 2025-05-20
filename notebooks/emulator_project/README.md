

## URLS 

- https://gist.github.com/dhruvbalwada/ad10bd40387b810e74d5e98aee13c41e
- https://github.com/camlab-ethz/poseidon?tab=readme-ov-file

## setup poseidon

In shell : install poseidon & dependencies

```
python -m venv poseidon_env
source poseidon_env/bin/activate

git clone https://github.com/camlab-ethz/poseidon
cd poseidon
pip install -e .

python
```

In python : load a pretrained model

```
>>> from scOT.model import ScOT
>>> model = ScOT.from_pretrained("camlab-ethz/Poseidon-B")
```