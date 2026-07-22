# Ashwani Kushwaha — Portfolio & Notes

Static portfolio and interactive notes for GitHub Pages. No build step.


## Shared format

Every page uses the same shell:

- styles: `assets/css/site.css` (one CSS file)
- scripts: `assets/js/site.js` (one JS file; notes that need demos load it)
- nav: brand → Home / Explore / About / Contact
- footer: Learn & explore · LinkedIn

## Site map

```text
index.html                 Profile / CV
writing/index.html         Explore index (add new cards here)
essays/ai-agent/           AI Agent note
essays/ml-regression/      Peeping Inside Black Box — Regression
essays/ml-classification/  Peeping Inside Black Box — Classification
essays/ml-black-box/       Series hub (links to both parts)
assets/css/site.css
assets/js/site.js
assets/images/profile/ashwani.jpg
assets/images/ml/          ML figures
tools/peeping_blackbox.py
```

## ML images wired into the note

Used in Part I:

- `Example_Plot.png`, `image_b_good.png`, `image_b_bad.png`, `image_b_derivative.png`
- `two_neuron.png`, `Square.png`, `Cube.png`, `four_neurons.png`, `Multiply.png`
- `tanhimage_b_good.png`, `tanhimage_b_bad.png`

Used in Part II:

- `blob.png`, `Sigmoid_blob2.png`
- `softmax2blob.png`, `2_D_Softmax.png`
- `One_dimensional_problem_square.png`
- `One_dimensional_problem_sin.png`, `One_dimensional_Sin_Lossfn.png`
- `Concen.png`, `Concen_softmax.png`
- `Sigmoid_1D_Plots_comb1.png`, `Sigmoid_1D_Plots_comb2.png`
- `Sigmoid_2D_Plots_comb.png`, `Sigmoid_2D_Plots_comb1.png`

Present in `assets/images/ml/` but not yet referenced in the HTML (embeddings / extras):

- `CBOW.png`, `Embedding_*.png`, `Embed_*.png`
- `Concen_line.png`, `Contour_blob2.png`, `counout_*.png`
- `one_dsimple.png`, `one_dcomplex.png`, `one_neuron.png`, `output.png`
- remaining `Sigmoid_*` variants

## Publish

GitHub → Settings → Pages → Deploy from branch → `main` / root.
