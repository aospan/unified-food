### Unified food project

## DISCLAIMER: use this information at your own risk

- **./ingredients** - list of substances available for mixing. Widely available plants and food ingredients recommended. For example: whole oat flour;
- **./profiles** - list of human body nutritions required to survive and thryve. For example: healthy adult (men and woman);

## How to use:
Calculate required ingredients proportions to feed human with specified profile (for example, healthy_adult.yaml):

    ./compile_food.py --profile profiles/healthy_adult.yaml
       --ingredient ingredients/whole_oat_flour.yaml
       --ingredient ingredients/milled_flax.yaml 
       --output myblend.yaml
