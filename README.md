## HashData

HashData created by Sam Brown (samdanielbrown@gmail.com).

## Description

A command line Hash/Encryption/Encoding function detector, After seeing lots of people in the past struggling to identify various hashes and encodings etc I decided to make a simple tool to do it for them. The listings aren't complete and will generally give numerous possibilities for each input due to the nature of a lot of functions having output in a similar format. All the regexs used are provided in a seperate text file foranyone whoever needs them for anything.

## Usage

git clone https://github.com/sam-b/HashData.git  
cd HashData  
ruby HashData.rb  
and then paste in hashes when prompted.  

## Supports

- Adler32
- Blowfish(Eggdrop), Blowfish(OpenBSD)
- CRC-16, CRC-16-CCITT
- CRC-32, CRC-32B
- CRC-96(ZIP)
- Domain Cached Credentials, Domain Cached Credentials 2
- DES(Unix), DES(Oracle)
- FCS-16, FCS-32
- FNV-132, FNV-164
- GOST R 34.11-94
- GHash-32-3, GHash-32-5
- Haval-128, Haval-160, Haval-192, Haval-224, Haval-256
- Joaat
- Keccak-224, Keccak-256, Keccak-384, Keccak-512
- Lineage II C4
- LM
- Lotus Domino
- MD2, MD4, MD5
- MD5(Joomla), MD5(osCommerce), MD5(PalshopCMS)
- MD5(APR), MD5(Cisco PIX), MD5(Unix)
- MD5(IP.Board), MD5(MyBB), MD5(phpBB3), MD5(WordPress)
- MySQL3.x, MySQL4.x, MySQL5.x
- MSSQL(2000), MSSQL(2005), MSSQL(2008)
- NTLM
- RAdmin v2.x
- RIPEMD-128, RIPEMD-160, RIPEMD-256, RIPEMD-320
- SAM(LM_Hash:NT_Hash)
- SHA-1, SHA-1(Django), SHA-1(MaNGOS), SHA-1(MaNGOS2)
- SHA-224
- SHA-256, SHA-256(Django), SHA-256(Unix)
- SHA-384, SHA-384(Django)
- SHA-512, SHA-512(Drupal), SHA-512(Unix)
- SSHA-1
- Skein-256, Skein-256(128), Skein-256(160), Skein-256(224)
- Skein-512, Skein-512(128), Skein-512(160), Skein-512(224), Skein-512(256), Skein-512(384)
- Skein-1024, Skein-1024(384), Skein-1024(512)
- Snefru-128, Snefru-256
- Tiger-128, Tiger-160, Tiger-192
- VNC
- Whirlpool
- XOR-32

## Development

Development is on going and new hashes are added sporadically and when requested and errors are fixed whenever reported.

Support for files of hashes coming soon.

## Contact
samdanielbrown@gmail.com or @sam_bwut for any questions of issues
