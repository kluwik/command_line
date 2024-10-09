# Assignment

> Perform steps 1-4 being located in your home directory. At step 6 you will be asked to change the directory. All further actions should be executed from that location. 
  
> Use paths relative to the locations you are in. Do not use absolute paths. For example, if you are asked "Being located in the directory `/home/user/dir/subdir` change to directory `/home/user/dir/`", the correct answer would be `cd ../` or `cd ..`, while `cd /home/user/dir/` won't count.

1. Download the archive by the link [https://zenodo.org/records/13858866/files/astex_diverse_set.tar.gz](https://zenodo.org/records/13858866/files/astex_diverse_set.tar.gz).

2. Decompress the archive. 

Check the list of files in your current directory. See, that the folder `data/` appeared - it was extracted from the archive. The archive file is still there but it is not needed anymore. It is a good practice to mind order in your files, especially on the server with other users. So, [see step 3].

3. Remove the archive file.

4. Create the folder `binding_benchmark/`.

5. Move the folder `astex_diverse_set` from `data/` to `binding_benchmark/`. Remove the folder `data/`.

6. Change to the directory `binding_benchmark/astex_diverse_set/`. Remove the following folders and files: `alphafold_server_terms_of_service/` `plots/` `astex_diverse_sequences.fasta`.

7. Create the folder `astex_proteins/` and move folders `astex_diverse_predicted_structures/` `astex_diverse_holo_aligned_predicted_structures` into `astex_proteins/`.

8. Write the list of files into a file `astex_ids.txt`.

9. Compress `astex_ids.txt` and folder `astex_proteins/` into the archive `astex.zip` into your home directory.

10. Transfer the zip archive to your local machine using scp command. Remember that scp command should be launched in the terminal or command line on your local machine.
