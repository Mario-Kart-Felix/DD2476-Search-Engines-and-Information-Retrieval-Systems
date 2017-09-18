# DD2476-Search-Engines-and-Information-Retrieval-Systems
Implementation of a spellchecker using the Levenshtein distance, for integration to the course's java skeleton. If the user's query to the search engine doens't exist in the index, the Spellchecker replaces the query with another that has the minimum editing distance with the original and exists in the index. 

## Instructions to compile and run in Linux
The scripts for compiling and running the search engine (compile_all.sh, run_search_engine.sh) in Linux, have been edited to integrate the Spellchecker. For use in Windows, edit the compile_all.bat and run_search_engine.bat accordingly.

1) Unzip the daviswiki.zip file in the current directory
2) ./compile_all.sh
3) ./run_search_engine.sh
4) Try out a query!
