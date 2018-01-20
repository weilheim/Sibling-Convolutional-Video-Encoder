# Sibling-Convolutional-Video-Encoder

Ground-truth caption should be stored in a json file with the following format:
{video_id_1(str): {'sentence': [sentence_1, sentence_2, ...], 'split': 'train' / 'val' / 'test'}, 
 video_id_2(str): {'sentence': [sentence_1, sentence_2, ...], 'split': 'train' / 'val' / 'test'}, 
 ...}
 
Video features should be stored in a h5 file with the following format:
video_id_1(str): feature(ndarray)   # h5 dataset
video_id_2(str): feature(ndarray)   # h5 dataset
...
