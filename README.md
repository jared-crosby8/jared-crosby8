# Jared Crosby

**Recommendation Systems Engineer**

## Impact

Recommendation systems drive 35% of platform revenue. Every 1% improvement in recommendation quality impacts millions of user experiences and significant business metrics.

## Production Scale

### 📊 Performance Metrics

| Metric | Value | Impact |
|--------|-------|--------|
| Daily Predictions | 500M+ | System-wide personalization |
| Click-Through Rate | 3.2% | User engagement |
| Conversion Lift | 28% | Revenue impact |
| Inference Latency (p95) | 45ms | User experience |
| Cold-Start Coverage | 94% | New user experience |
| Active Models | 15 | Diversity of approaches |

## Technical Approach

### Collaborative Filtering
Using matrix factorization and advanced techniques to find patterns in user-item interactions. Effective at scale with proper optimization.

### Content-Based Methods
Using embeddings and item features to recommend similar items. Particularly effective for cold-start problems where historical data is limited.

### Learning-to-Rank
Combining multiple ranking signals through gradient boosting and neural networks. Optimizing the entire ranking pipeline, not just individual components.

### Real-Time Features
Computing user features in real-time to capture latest behavior and context. Critical for current recommendations vs stale historical data.

### Continuous Testing
A/B testing every algorithm change against business metrics. Statistical rigor ensuring improvements are real and significant.

## Key Challenge

The cold-start problem remains significant—how to recommend for new users with no history. Content-based bootstrapping helps, but contextual signals are critical. We're approaching 94% new user coverage through multi-faceted strategies.

## Optimization Efforts

**Latency:** Reducing inference time from 200ms to 45ms through model optimization, caching, and smarter feature computation.

**Coverage:** Extending recommendations to long-tail items using hybrid approaches and exploration strategies.

**Diversity:** Ensuring recommendations aren't too narrow, providing serendipitous discoveries alongside obvious choices.

**Fairness:** Monitoring for bias in recommendations across user demographics and item popularity.

## Technology Stack

Matrix factorization, Gradient boosting, Neural networks, Embedding models, Real-time feature stores, A/B testing frameworks

---

*Personalization at scale.*