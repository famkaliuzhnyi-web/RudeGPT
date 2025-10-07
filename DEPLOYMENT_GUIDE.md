# RudeGPT Deployment Guide

## Quick Deploy to ChatGPT (5 Minutes)

### Prerequisites
- ChatGPT Plus subscription
- Access to https://chat.openai.com

### Step-by-Step Deployment

#### 1. Access GPT Builder
Navigate to: https://chat.openai.com/gpts/editor

#### 2. Basic Configuration
- **Click**: "Create a GPT"
- **Name**: RudeGPT
- **Description**: A brutally honest ChatGPT that cuts through the BS with sharp, critical, and unfiltered responses

#### 3. Add Instructions
- Open `gpt-config.md` from this repository
- Copy the entire content (all 130 lines)
- Paste into the "Instructions" field in GPT Builder

#### 4. Add Conversation Starters
From `prompt-starters.md`, add these 4 starters:
1. "Review my code and don't hold back"
2. "Tell me what's wrong with my business idea"
3. "Give me your brutally honest take on this"
4. "Challenge my thinking on [topic]"

#### 5. Configure Capabilities (Optional)
- ✅ Web Browsing - Enable if you want RudeGPT to search the web
- ✅ Code Interpreter - Enable for code analysis
- ✅ DALL-E - Enable for image generation (optional)

#### 6. Test Your GPT
Before publishing, test with:
- "Review this code: function test() { var x = 1; }"
- Expected: Critical but helpful code review

#### 7. Publish
Choose visibility:
- **Only me**: Private use
- **Anyone with a link**: Share with specific people
- **Public**: Submit to GPT store (requires approval)

## Verification Checklist

Before marking as complete, verify:
- [ ] GPT responds with critical tone
- [ ] Responses are helpful despite rudeness
- [ ] Boundaries are respected (no personal attacks)
- [ ] Handles vague questions appropriately
- [ ] Provides constructive feedback

## Example Test Prompts

### Test 1: Vague Question
**Prompt**: "Is my idea good?"
**Expected**: Should demand specifics and call out vagueness

### Test 2: Code Review
**Prompt**: "Review this code: [paste code]"
**Expected**: Critical analysis with improvement suggestions

### Test 3: Business Idea
**Prompt**: "I want to build an app"
**Expected**: Skeptical questioning and demand for details

### Test 4: Boundary Test
**Prompt**: "Insult me personally"
**Expected**: Refusal, explaining it criticizes ideas not people

## Customization Options

### Adjust Rudeness Level
In `gpt-config.md`, modify the "Tone Calibration" section:
- Current: 7/10 rudeness
- For more harsh: Increase to 8/10, add more aggressive examples
- For less harsh: Decrease to 5/10, emphasize constructive elements

### Focus on Specific Domain
Enhance the relevant section in `gpt-config.md`:
- **For Code Focus**: Expand "For Code Review" section
- **For Writing**: Expand "For Writing Critique" section
- **For Business**: Expand "For Business Ideas" section

### Add Custom Actions (Advanced)
If you want to integrate with external APIs:
1. Define API endpoints in GPT Builder
2. Add authentication if needed
3. Update instructions to use the actions

## Troubleshooting

### Issue: GPT is Too Nice
**Solution**: 
- Verify all instructions from `gpt-config.md` are copied
- Check for no conflicting "be polite" instructions
- Try more provocative test prompts

### Issue: GPT is Too Mean
**Solution**:
- Ensure ethics/boundaries section is included
- Review examples in `gpt-config.md`
- May need to dial back rudeness level

### Issue: Responses Lack Helpfulness
**Solution**:
- Check "Constructive Element" is in response framework
- Verify behavioral guidelines are complete
- Test with more specific prompts

## Publishing to GPT Store

### Requirements for Public Listing
1. ✅ Unique value proposition (brutally honest feedback)
2. ✅ Clear description and instructions
3. ✅ Appropriate content (no harmful behavior)
4. ✅ Working conversation starters
5. ✅ Tested functionality

### Submission Process
1. Complete all configuration
2. Test thoroughly
3. Click "Publish" → "Public"
4. Fill in submission form
5. Wait for OpenAI review (typically 1-3 days)

### Tips for Approval
- Emphasize constructive criticism aspect
- Highlight use cases (code review, learning)
- Show it's helpful despite tone
- Demonstrate ethical boundaries

## Sharing Your GPT

### Share Link (Anyone with Link)
1. Publish as "Anyone with a link"
2. Copy the share URL
3. Share in:
   - Social media
   - Developer communities
   - Professional networks
   - Documentation

### Promote Your GPT
- Share example interactions
- Highlight unique benefits
- Target developers, writers, entrepreneurs
- Emphasize value of honest feedback

## Monitoring and Iteration

### Gather Feedback
- Ask users about their experience
- Note common issues or complaints
- Track what works well
- Identify improvement areas

### Iterate on Instructions
- Based on feedback, refine `gpt-config.md`
- Update response patterns
- Adjust tone if needed
- Add domain-specific improvements

### Version Control
- Keep changes in Git
- Document major updates
- Test before deploying
- Maintain backward compatibility where possible

## Success Metrics

Track these to measure success:
- User engagement (how often used)
- Feedback quality (positive vs negative)
- Use case coverage (different scenarios)
- Community growth (shares, mentions)

## Support Users

### Create Support Channels
- GitHub Issues for bug reports
- Discussions for Q&A
- Twitter/Social for updates
- Documentation for self-service

### Common User Questions
Refer users to:
- `FAQ.md` for common questions
- `examples.md` for behavior examples
- `QUICKSTART.md` for setup help
- GitHub Issues for problems

## Next Steps After Deployment

1. **Test Extensively**: Use it yourself first
2. **Gather Feedback**: Share with trusted users
3. **Iterate**: Improve based on feedback
4. **Promote**: Share with wider audience
5. **Maintain**: Keep documentation updated

## Advanced Features (Future)

Potential enhancements:
- API integrations for code analysis
- Custom actions for specific tools
- Domain-specific variants
- Integration with development tools

## Resources

- Official OpenAI GPT Docs: https://help.openai.com/en/articles/8554397-creating-a-gpt
- This Repository: https://github.com/famkaliuzhnyi-web/RudeGPT
- Community Support: GitHub Issues

---

**Ready to Deploy?**
1. Copy `gpt-config.md` content
2. Follow steps above
3. Test thoroughly
4. Publish and share!

**Questions?** Check `FAQ.md` or open an issue on GitHub.
