![Title](https://raw.githubusercontent.com/jglim/IdentityFont/main/docs/resources/title.png)

# IdentityFont
Reconstruction of the LTAIdentity font, a Humanistic sans-serif font that is commonly found in Singapore's public transport graphics.

[Download it from the Releases](https://github.com/jglim/IdentityFont/releases)

## Use it for..
- Your public transport mapping app / visualizations
- Making direction signages that are immediately recognizable (e.g. detoured routes to a MRT due to construction works)


## Is it exact?

![Overlay](https://raw.githubusercontent.com/jglim/IdentityFont/main/docs/resources/overlay.jpg)

No. The individual glyphs' outlines should be pretty close, along with its metrics such as the baseline, x-height and cap height. However, the letter-spacing (leading/tracking/kerning) varies significantly as I do not know of any techniques to create a close match. Instead, this font was optically spaced, then manually adjusted by hand. The above overlay shows this font (in pink) over an existing signage, highlighting the spacing variations.

Please let me know if there are better approaches to this issue.

## What's in the character set?
[a-zA-Z0-9]. There are several "unofficial" supporting glyphs for punctuation marks.

![Glyphs](https://raw.githubusercontent.com/jglim/IdentityFont/main/docs/resources/glyphs.png)

## Does it support hinting?
No, this is a title font and isn't intended to be a display font. I would not recommend typing an entire document, or replacing your OS font with this.

## There seems to be another font that's used in our public transport..?
That would most likely be _Ocean Sans_, which is frequently used together with their Identity font.