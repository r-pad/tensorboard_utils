# tensorboard_utils
Tools for using tensorboard logs

## Usage
```
python scripts/plot_tensorboard.py \
    --image-prefix tensorboard_plot_ \
    --log-dirs \
    path/to/train/logs \
    path/to/valid/logs \ \
    --log-labels \
    'Train' \
    'Valid' \
    --scalar-tags 'loss' \
    --ylabels 'Loss' \
    --max-step 10000
```
