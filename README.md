# CV HW3: Domain Adaptation

## Data
A json file which contains 
* keys: 'categories', 'images', 'annotations'
* inside 'categories': a list of dict, where each element is {'id': 1, 'name': 'person'}, mapping id to class names.
* inside 'images': a list of dict, where each dict is sth like {'id': 0, 'width': 2048, 'height': 1024, 'file_name': 'org/train/0000.png'}, idicating information of each file.
* inside 'annotations']: a list of dict, where each dict is sth like {'id': 0, 'image_id': 905, 'category_id': 1, 'iscrowd': 0, 'area': 3212, 'bbox': [1251, 362, 49, 113]}, indicating information of each bbox.
