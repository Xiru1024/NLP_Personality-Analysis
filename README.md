# NLP_Personality-Analysis
# Personality Analysis from Conversations

NLP project analyzing how personality traits (Big Five) relate to conversation patterns and emotions.

## Dataset

- **Main**: [PELD Dataset](https://github.com/preke/PELD) - `Dyadic_PELD.tsv`
- **Emotion Lexicon**: [NRC VAD Lexicon](https://github.com/Priya22/EmotionDynamics/tree/master/lexicons)

## Setup

```bash
# Install dependencies
pip install pandas numpy scikit-learn nltk gensim transformers matplotlib seaborn

# Download NLTK data
python -m nltk.downloader wordnet punkt stopwords

# Create data folder and download the datasets to it
mkdir data
```

## Project Tasks

1. **Vocabulary Analysis** - Extract vocabulary metrics (size, repetitions, confirmation/negation words)
2. **Topic Evolution** - Track how speakers introduce new topics using LDA
3. **Emotion Patterns** - Analyze valence/arousal/dominance scores per personality
4. **Trait-Specific Analysis** - Compare conversation patterns across personality types
5. **Embedding Similarity** - Match conversations to personality trait definitions
6. **Personality Prediction** - Build ML models to predict personality scores from conversations

## Files

- `main.ipynb` - All analysis code
- `NLP_project.pdf` - Detailed project requirements
- `data/` - Place downloaded datasets here

## Big Five Traits

- **Extraversion**: Talkative, sociable, adventurous
- **Agreeableness**: Cooperative, gentle, good-natured
- **Conscientiousness**: Responsible, organized, persistent
- **Neuroticism**: Anxious, tense, emotional
- **Openness**: Creative, intellectual, imaginative

## 📈 Key Analyses

1. **Vocabulary Analysis**: Track vocabulary size, repetitions, confirmation/negation tokens
2. **Topic Modeling**: LDA-based topic evolution with coherence and perplexity metrics
3. **Emotion Patterns**: VAD dimension analysis using NRC lexicon
4. **Personality Trait Analysis**: Individual trait-based conversation patterns
5. **Embedding Similarity**: Cosine similarity between conversation embeddings and personality definitions
6. **Predictive Modeling**: ML/DL models for personality score prediction

## 🎓 Personality Trait Definitions

- **Extraversion**: Talkative, sociable, adventurous, open
- **Agreeableness**: Good-natured, cooperative, mild, gentle
- **Conscientiousness**: Responsible, scrupulous, persevering, tidy
- **Emotional Stability**: Calm, composed, not hypochondriacal, poised
- **Openness**: Intellectual, artistic, imaginative, polished

## 📊 Expected Outputs

- Vocabulary evolution plots by speaker and personality type
- Topic distribution visualizations
- Emotion-personality correlation tables
- Personality prediction model performance metrics
- Embedding similarity scores

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
