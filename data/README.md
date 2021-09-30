# Tagging the Tarikh as-Sudan and the Tarik al-Fattash

## Start with the Tarikh as-Sudan (tarikh-as-soudan-fra.txt)

1. Mark Paragraphs with \<p\> and \</p> tags.
2. Mark references to notes in text. E.g., on page 129:

"sultan de Agadez’, et la termina au cours de la vingt-deuxième"

Becomes

"sultan de Agadez<ref target="1"/>, et la termina au cours de la vingt-deuxième"
3. Mark notes where they have been missed (many notes have been added with regular expressions)
4. If there is Arabic in a footnote, put it in tags <foreign>ZZZ</foreign>. You may need to put the Arabic on a separate line becuase of the letf/right, right/left writing conflict.
