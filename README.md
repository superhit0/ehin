# EHIN

## Citation- [Wiley Online Library](https://onlinelibrary.wiley.com/doi/pdf/10.1111/exsy.12296)
## Paper Link- [EHIN](https://drive.google.com/file/d/14YiZnw4CQBdnRY38JryR5XjaC7i1a2U6/view?usp=sharing)

Build from Source:
- Go to Source Directory.
- Install maven.
- mvn clean package.
- Get Jar from target folder

Using jar:
- java -jar ehin-1-jar-with-dependencies.jar -min [int--minUtil] -i [string-path--input-file] -o [string-path--output-file] -sup [boolean--activate-subtree-pruning] -tm [boolean--activate-transaction-merging] -c [int--maximum-transactions]
- Output Itemsets in output file and stats printed on console.
