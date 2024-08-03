
# Run the Tool

cd TGxss02
chmod +x tgxss02.py

# More information 

# TGxss02

**TGxss02** is a tool for finding XSS vulnerabilities in web applications.

# setup.py

pip install .

## Usage

# Note:- if first command not run than try secound command.

cd TGxss02

# single url

python tgxss02.py -u http://example.com -p payload.txt -r ./results

./tgxss02.py -u http://example.com -p payload.txt  -r ./result

# multiple url

python tgxss02.py -l urls.txt -p payload.txt -r result

./tgxss02.py -l urls.txt -p payload.txt  -r ./result

# multiple domains/sub-domains 

python tgxss02.py -dL domains.txt -p payload.txt -r result

./tgxss02.py -dL domains.txt -p payload.txt -r ./result


# TGxss02
