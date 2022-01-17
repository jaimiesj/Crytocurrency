# Crytocurrency

## Update
I was able to resolve the issue with the difference in rows by concatinating and keeping the index of the crypto_df (when it concatinated, it did not "join" correctly). I ran into a challenge with the scaled data from the MinMaxScaler, when I had to convert it into a dataframe, as I was unable to concatinate an array. I attempted generating a dataframe and when I concatinated it, it resulted in over 100 columns, resulting in the scatterplot a bit difficult to read.

## Original
I generated as much code as I could, including the code I would use, despite not being able to run it due to an error. The crypto_df generated 532 rows, but after scaling it, I presume, the rows doubled and I wasn't able to determine how to resolve that so when I tried to incorporate the class into the clustered_df, the index for the predictions vs the clustered_df didn't match.
