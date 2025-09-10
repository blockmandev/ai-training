# QoraNet Task Poster Guide & FAQ
## Complete Guide for Resource Providers

---

## Quick Start: Post Your First Task

### What You Need
- **Datasets** (images, text, code, etc.)
- **Training scripts** (optional but recommended)
- **QOR tokens** for staking (100-2500 QOR depending on tier)
- **Quality bond** (automatically calculated)

### 5-Minute Setup
1. **Upload Resources** - Drag & drop your datasets
2. **Set Duration** - Choose 5 minutes to 6 hours  
3. **Preview Rewards** - See estimated QOR earnings
4. **Stake Tokens** - Select your tier (Bronze to Platinum)
5. **Post Task** - Get paid while AI trains on your data

---

## Staking Tiers & Benefits

| Tier | Stake Required | Max Task Size | Concurrent Tasks | Reward Multiplier | Bond Reduction |
|------|---------------|---------------|------------------|-------------------|----------------|
| **Bronze** | 100 QOR | 30 minutes | 1 | 0.8x (36% rewards) | 0% |
| **Silver** | 500 QOR | 2 hours | 3 | 1.0x (45% rewards) | 20% |
| **Gold** | 1,000 QOR | 6 hours | 5 | 1.2x (54% rewards) | 40% |
| **Platinum** | 2,500 QOR | Unlimited | 10 | 1.5x (67.5% rewards) | 60% |

### Recommended Starting Tier
**Gold (1,000 QOR)** - Best balance of investment vs rewards. Pays for itself in 1-2 successful tasks.

---

## Earnings Calculator

### Example Task: 1 Hour Training (1800 blocks)
- **Total Reward Pool**: 90,000 QOR (1800 × 50 QOR per block)
- **Your Share**: 45% base rate

| Your Tier | Your Earnings | ROI per Task |
|-----------|---------------|--------------|
| Bronze | 32,400 QOR | 324x stake |
| Silver | 40,500 QOR | 81x stake |
| Gold | 48,600 QOR | 49x stake |
| Platinum | 60,750 QOR | 24x stake |

**Note**: Higher tiers have better absolute earnings despite lower ROI percentages.

---

## DO's - Best Practices

### Data Preparation
✅ **Clean Your Data**
- Remove corrupted files
- Ensure consistent formatting
- Label data clearly
- Include metadata/descriptions

✅ **Optimize File Sizes**
- Compress large datasets appropriately
- Use efficient formats (PNG vs BMP, CSV vs Excel)
- Remove unnecessary duplicates

✅ **Provide Context**
- Describe what the data contains
- Explain intended use case
- Set realistic expectations
- Include any preprocessing steps

✅ **Quality Scripts**
- Write efficient, well-commented code
- Test scripts before uploading
- Include documentation
- Optimize for GPU training

✅ **Set Realistic Timelines**
- Small datasets: 5-30 minutes
- Medium datasets: 30 minutes - 2 hours
- Large datasets: 2-6 hours
- Massive datasets: 6+ hours (Platinum only)

✅ **Build Reputation**
- Start with smaller, high-quality tasks
- Respond to feedback quickly
- Fix issues promptly
- Engage with the community

---

## DON'Ts - Common Mistakes

### Data Issues
❌ **Don't Upload Corrupted Data**
- Broken files waste GPU time
- Results in automatic task failure
- Damages your reputation score
- Leads to bond forfeiture

❌ **Don't Use Copyrighted Material**
- Violates platform terms
- Can result in legal issues
- Leads to account suspension
- Causes 100% stake slashing

❌ **Don't Post Duplicate Tasks**
- Same data uploaded multiple times
- Wastes network resources
- Reduces rewards for everyone
- Triggers anti-spam measures

❌ **Don't Misrepresent Data**
- Claiming fake dataset sizes
- Promising unrealistic results
- Mislabeling data types
- Leads to reputation penalties

### Economic Mistakes
❌ **Don't Overstake Initially**
- Start with Bronze/Silver tier
- Learn the system first
- Build reputation gradually
- Upgrade tier after success

❌ **Don't Post Tasks Too Large for Your Tier**
- Bronze: Max 30 minutes
- Silver: Max 2 hours
- Gold: Max 6 hours
- Exceeding limits = automatic rejection

❌ **Don't Rush Quality Bonds**
- Understand bond requirements
- Ensure sufficient QOR balance
- Calculate total cost upfront
- Don't risk more than you can lose

---

## Task Types & Examples

### Image Training Tasks
```
Good Example:
- Dataset: 10,000 cat photos (clean, labeled)
- Script: Fine-tune ResNet for cat breed classification
- Duration: 2 hours
- Expected output: 95%+ accuracy model

Bad Example:
- Dataset: Random internet images (unlabeled, mixed quality)
- Script: Generic training script
- Duration: 6 hours
- Expected output: "Some kind of image classifier"
```

### Text/NLP Tasks
```
Good Example:
- Dataset: 50,000 customer reviews (preprocessed, sentiment labeled)
- Script: Fine-tune BERT for sentiment analysis
- Duration: 1 hour
- Expected output: Production-ready sentiment model

Bad Example:
- Dataset: Raw web scraping data (unprocessed, duplicates)
- Script: Basic text classifier
- Duration: 4 hours
- Expected output: "Text analysis thing"
```

### Code Training Tasks
```
Good Example:
- Dataset: 100,000 Python functions (documented, tested)
- Script: Fine-tune CodeBERT for code completion
- Duration: 3 hours
- Expected output: VS Code extension ready model

Bad Example:
- Dataset: Random GitHub files (uncommented, mixed languages)
- Script: Generic code model
- Duration: 5 hours
- Expected output: "Code understanding model"
```

---

## Quality Bond System

### How It Works
- **Bond Amount**: 10% of expected total rewards
- **Purpose**: Ensures task quality and completion
- **Reduction**: Higher tiers get lower bonds
- **Return**: Full bond returned on successful completion

### Bond Calculation Examples
```
1 Hour Task (90,000 QOR total rewards):
- Bronze: 9,000 QOR bond (10% of 90,000)
- Silver: 7,200 QOR bond (20% reduction)
- Gold: 5,400 QOR bond (40% reduction)  
- Platinum: 3,600 QOR bond (60% reduction)
```

### Bond Forfeiture Reasons
- **Task Failure**: Training doesn't complete successfully
- **Poor Quality**: Data doesn't meet minimum standards
- **Fraud**: Fake or misleading information
- **Copyright**: Using protected material without permission

---

## Reputation System

### Reputation Scoring
- **Starting Score**: 100 points
- **Score Range**: 0-1000+ points
- **Impact**: Affects rewards, queue priority, bond requirements

### How to Gain Reputation
- **Successful Task**: +10 points
- **High Quality Data**: +15 points
- **Innovative Scripts**: +20 points
- **Community Feedback**: +5 points
- **Model Reuse**: +3 points per reuse

### How to Lose Reputation
- **Failed Task**: -20 points
- **Poor Quality**: -15 points
- **Deadline Miss**: -10 points
- **Copyright Issue**: -100 points
- **Fraud Attempt**: -500 points + ban

### Reputation Benefits
| Score Range | Benefits |
|-------------|----------|
| 0-99 | Reduced rewards, higher bonds |
| 100-199 | Standard treatment |
| 200-299 | 10% reward bonus |
| 300-499 | 20% reward bonus, priority queue |
| 500+ | 30% reward bonus, beta features |

---

## Technical Requirements

### Supported File Formats
**Images**: PNG, JPG, TIFF, BMP, WebP
**Text**: TXT, CSV, JSON, XML, MD
**Code**: PY, JS, CPP, JAVA, GO, RS
**Models**: PTH, ONNX, H5, PB
**Archives**: ZIP, TAR, 7Z (auto-extracted)

### File Size Limits
- **Single File**: Max 5GB
- **Total Dataset**: Max 100GB per task
- **Archive Files**: Max 50GB compressed

### Script Requirements
- **Languages**: Python (preferred), R, Julia
- **Dependencies**: Include requirements.txt
- **GPU Support**: CUDA-compatible code recommended
- **Memory**: Optimize for 16GB+ GPU memory

---

## Troubleshooting

### Common Issues

**Q: My task failed during training**
A: Check your data quality, script errors, and file formats. Failed tasks forfeit quality bonds.

**Q: I can't post large tasks**
A: Upgrade your staking tier. Bronze is limited to 30 minutes, Silver to 2 hours.

**Q: My reputation score dropped**
A: Review your recent tasks for quality issues. Focus on smaller, high-quality tasks to rebuild.

**Q: Bond amount seems too high**
A: Bonds are 10% of expected rewards. Higher staking tiers get reduced bond requirements.

**Q: Task is taking longer than expected**
A: GPU availability varies. Platinum tier gets priority queue access.

### Getting Help
- **Discord**: #task-poster-help
- **Documentation**: docs.qoranet.ai
- **Support Tickets**: support@qoranet.ai
- **Community Forum**: forum.qoranet.ai

---

## FAQ

### General Questions

**Q: Do I pay anything to post tasks?**
A: No upfront payment! You stake QOR (refundable) and post a quality bond (returned on success). You actually EARN money for posting good tasks.

**Q: Who owns the trained models?**
A: All models become public goods on IPFS. You retain rights to your original data but trained models are open source.

**Q: Can I train private/confidential data?**
A: Data is encrypted during training. Trainers cannot access raw data, only the training process.

**Q: How long until I see results?**
A: Depends on network congestion and task size. Platinum tier gets priority processing.

### Economic Questions

**Q: How much can I earn?**
A: Varies by tier and task size. Gold tier earns ~50,000 QOR for 1-hour tasks. At launch, this could be $500-5000 depending on token price.

**Q: When do I get paid?**
A: 50% immediately, 50% vested over 30 days to prevent market dumping.

**Q: What if the token price drops?**
A: You're earning a deflationary asset. With 50% of revenues burned, token should appreciate over time.

**Q: Can I lose money?**
A: Only your quality bond is at risk. Stakes are returned when you stop posting. Choose appropriate tier sizes.

### Technical Questions

**Q: What happens to my data?**
A: Encrypted, used for training only, then deleted. Original data remains yours.

**Q: Can I update tasks after posting?**
A: No. Plan carefully before posting. Failed tasks forfeit bonds.

**Q: Do I need to write code?**
A: Not required but recommended. Data-only tasks get lower reward multipliers.

**Q: What GPUs will train my models?**
A: Network uses consumer and professional GPUs. Tasks auto-matched to appropriate hardware.

---

## Success Stories & Examples

### Case Study 1: Indie Game Developer
- **Background**: Needed AI for NPC behavior
- **Task**: 2-hour training on player interaction data
- **Tier**: Gold (1,000 QOR stake)
- **Result**: Earned 48,600 QOR + got perfect NPC AI for free
- **ROI**: 4,860% return on stake

### Case Study 2: Research Lab
- **Background**: Academic research on medical imaging
- **Task**: 4-hour training on MRI scan dataset
- **Tier**: Platinum (2,500 QOR stake)
- **Result**: Earned 121,500 QOR + published paper using model
- **ROI**: 4,860% return + academic publication

### Case Study 3: Content Creator
- **Background**: Wanted AI to generate art in personal style
- **Task**: 30-minute training on artwork portfolio
- **Tier**: Silver (500 QOR stake)
- **Result**: Earned 20,250 QOR + personal AI art generator
- **ROI**: 4,050% return + custom creative tool

---

## Advanced Tips

### Maximizing Earnings
1. **Start Small**: Build reputation with quick, high-quality tasks
2. **Upgrade Gradually**: Move from Bronze → Gold → Platinum
3. **Batch Similar Tasks**: Post related datasets together
4. **Time Strategically**: Post during low-congestion periods
5. **Community Engagement**: Share insights, help others

### Risk Management
1. **Diversify Task Sizes**: Mix small and large tasks
2. **Quality First**: Better to post fewer, higher-quality tasks
3. **Monitor Reputation**: Keep score above 200 for bonuses
4. **Conservative Bonding**: Don't risk more than you can afford
5. **Stay Updated**: Follow platform updates and best practices

---

## Contact & Support

**Platform Links**
- Website: https://qoranet.ai
- Documentation: https://docs.qoranet.ai
- Discord: https://discord.gg/qoranet
- Twitter: https://twitter.com/qoranet_ai

**Support Channels**
- General Help: #general-help
- Technical Issues: #technical-support  
- Task Posting: #task-poster-help
- Economics Questions: #tokenomics-help

**Emergency Contact**
- Critical Issues: emergency@qoranet.ai
- Security Issues: security@qoranet.ai
- Legal Issues: legal@qoranet.ai

---

*Last Updated: Launch Version 1.0*
*This guide will be updated as the platform evolves*
