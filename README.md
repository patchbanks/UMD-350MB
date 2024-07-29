# UMD-350MB

The Universal MIDI Dataset 350MB (UMD-350MB) is a proprietary collection of 85,618 MIDI files curated for research and development within our organization. This collection is a subset sampled from a larger dataset developed for pretraining symbolic music models.

The field of symbolic music generation is constrained by limited data compared to language models. Publicly available datasets, such as the Lakh MIDI Dataset, offer large collections of MIDI files sourced from the web. While the sheer volume of musical data might appear beneficial, the actual amount of valuable data is less than anticipated, as many songs contain less desirable melodies with erratic and repetitive events.

The UMD-350MB employs an attention-based approach to achieve more desirable output generations by focusing on human-reviewed training examples of single-track melodies, chord progressions, leads and arpeggios with an average duration of 8 bars. This was achieved by refining the dataset over 24 months, ensuring consistent quality and tempo alignment. Moreover, the dataset is normalized by setting the timing information to 120 BPM with a tick resolution (PPQ) of 96 and transposing the musical scales to C major and A minor (natural scales).

## Melody Styles

A major portion of the dataset is composed of newly produced private data to represent modern musical styles.

| **Genre** | **Top Subgenres** |
|-----------|-------------------|
| **Pop**   | 1970s to 2020s Pop music |
| **EDM**   | Trance, House, Synthwave, Dance, Arcade |
| **Jazz**  | Bebop, Ballad, Latin-Jazz, Bossa-Jazz, Ragtime |
| **Soul**  | 80s Classic, Neo-Soul, Latin-Soul |
| **Urban** | Pop, Hip-Hop, Trap, R&B, Afrobeat |
| **World** | Latin, Bossa Nova, European |
| **Other** | Film, Cinematic, Game music and piano references |
|       	| *Actual MIDI files are unlabeled for unsupervised training.* |

## Dataset Access
Please note that this is a closed-source dataset with very limited access. Considerations for access include proposals for data augmentation, chord extraction and other enhancement methods, whether through scripts, algorithmic techniques, manual editing in a DAW or additional processing methods.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13126590.svg)](https://doi.org/10.5281/zenodo.13126590)


For inquiries about this dataset, please email us.
