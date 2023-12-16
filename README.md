# Bulma Extension For noUiSlider
Bulma extension SASS CSS for noUiSlider.js
To match Bulma slider styling and Bulma uses SASS.

## Features - _Ver. 0.1 "Range and Handle Styles"_
- Range and Handle Styling
  - 'Default' Square Handle & Round/Circle Handle
  - Colors; range & connects
  - Horizontal & Vertical Styling

## Usage
To be used in conjuction with the default noUiSlider css: apply Bulma-like styling with a styled slider class (default: `.styled-slider`). Therefore load after noUiSlider css wheater alone or built into Bulma.

Follows Bulma for size, color, and appearence as close as possible.  
`.is-[size]` and  `.is-circle` to apply size to the slider or make the handle appearence round.  
`.is-[color]` to apply color to the slider range, including `.is-light`, `.is-dark`, and `.is-inverted`.  
Use `.is-[color]-connect` to apply color to all connects within the slider.  
Build with `jsconnects` for `.is-[color]` styling on individual connects by applying the class via javascript.  
Build with `cssconnects` for `.is-[color]-connect-[n]` class styling for the slider applying to [n]th-child connects (default 5).

## Requirements

Based From:
- Bulma 0.9.4
- noUiSlider 15.7.1

Build Requirements:
- Dart SASS

## Build


- Independent: Use `.base.sass` to build standalone css with Dart SASS. Edit to include either/neither `cssconnects` or `jsconnects` for individual connect coloring.
- With Bulma: Either include `.base.sass` or include individual modules (`core`, `cssconnects`, `jsconnects`) as part of your custom Bulma base in the same manner as Bulma.

Edit `config` to modify the noUiSlider prefix to match noUiSlider.js if changed, to set the class name defining styled sliders, and shared generated style settings.  

## License

MIT
