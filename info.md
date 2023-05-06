# error with « w2v_vectors = w2v_model.wv »

https://stackoverflow.com/questions/71544767/keyedvectors-object-has-no-attribute-wv-for-gensim-4-1-2

instead of w2v_model.wv.vocab use kv_model.key_to_index.

has_index_for(key) : https://radimrehurek.com/gensim/models/keyedvectors.html

part 1.d
difference between distance and similarity
distance = how different 2 words are
similarity = how similar they are

psutil.Process(os.getpid()).memory_info().rss : to get the amount of memory currently being used by the current Python process.
os.getpid() : current process ID.
psutil.Process(pid) creates a Process object for the current process.
memory_info() : gives information about memory usage -> which are  rss(resident set size) and  amount of non-swapped physical memory used by a process.
rss :  returned by memory_info() it represents the amount of memory used by the process in bytes.
