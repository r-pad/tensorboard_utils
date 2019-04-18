# tensorboard_utils
Tools for using tensorboard logs

## Usage
```
python scripts/plot_tensorboard.py \
    --image_prefix tensorboard_plot_ \
    --log_dirs \
    path/to/train/logs \
    path/to/valid/logs \ \
    --log_labels \
    'Train' \
    'Valid' \
    --scalar_tags 'loss' \
    --ylabels 'Loss' \
    --max_step 10000
```
