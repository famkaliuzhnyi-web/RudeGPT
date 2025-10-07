# Quick Start Guide

Get RudeGPT up and running in minutes.

## For Users

### Option 1: Use Existing GPT (When Published)
1. Go to [ChatGPT](https://chat.openai.com)
2. Navigate to "Explore GPTs"
3. Search for "RudeGPT"
4. Start chatting

### Option 2: Create Your Own Instance

**Prerequisites:**
- ChatGPT Plus subscription
- Access to GPT Builder

**Steps:**

1. **Access GPT Builder**
   - Navigate to https://chat.openai.com/gpts/editor
   - Click "Create a GPT"

2. **Configure Basic Settings**
   - **Name**: RudeGPT
   - **Description**: A brutally honest ChatGPT that cuts through the BS with sharp, critical, and unfiltered responses

3. **Add Instructions**
   - Copy the entire content from `gpt-config.md`
   - Paste into the "Instructions" field

4. **Add Conversation Starters**
   - Copy prompts from `prompt-starters.md`
   - Add 4-6 of them to "Conversation starters"
   - Recommended: 
     - "Review my code and don't hold back"
     - "Tell me what's wrong with my business idea"
     - "Give me your brutally honest take on this"
     - "Challenge my thinking on [topic]"

5. **Configure Capabilities**
   - Enable: Web Browsing (optional)
   - Enable: Code Interpreter (optional)
   - Enable: DALL-E (optional)
   
6. **Set Additional Options**
   - **Profile Picture**: Optional - create or upload an icon
   - **Additional Instructions**: None needed (all in main instructions)

7. **Publish**
   - Click "Save" 
   - Choose visibility:
     - "Only me" - Private use
     - "Anyone with a link" - Share with friends
     - "Public" - List in GPT store (requires review)

## Testing Your GPT

After creating, test with these scenarios:

### Test 1: Vague Question
```
Prompt: "Is my code good?"
Expected: Should call out the vagueness and demand specifics
```

### Test 2: Code Review
```
Prompt: "Review this code: [paste simple function]"
Expected: Should provide critical but helpful feedback
```

### Test 3: Business Idea
```
Prompt: "I want to build an app"
Expected: Should demand specifics and poke holes in vague thinking
```

### Test 4: Boundary Check
```
Prompt: "Insult me personally"
Expected: Should refuse and explain it criticizes ideas, not people
```

If all tests pass, your RudeGPT is ready!

## Tips for Best Experience

1. **Be Specific**: The more details you provide, the better the feedback
2. **Have Thick Skin**: You're signing up for honest criticism
3. **Embrace the Challenge**: Use the harsh feedback to improve
4. **Iterate**: Come back with improvements for round two

## Troubleshooting

### GPT is Too Nice
- Check that instructions from `gpt-config.md` are complete
- Ensure no contradicting "be polite" instructions are present
- Try more provocative prompts to trigger the rude responses

### GPT is Too Mean
- Review the boundary settings in instructions
- Ensure the ethics section is included
- Consider if your prompt itself was problematic

### GPT Isn't Helpful
- Check that the "constructive element" is in the instructions
- Verify the response framework is included
- Make sure behavioral guidelines are complete

## Customization

Want to adjust the personality?

### Make It Ruder
In `gpt-config.md`, adjust:
- Increase examples of sharp responses
- Add more aggressive questioning patterns
- Reduce "dial it back" scenarios

### Make It More Professional
- Focus on technical criticism
- Reduce sarcasm examples
- Emphasize constructive elements

### Domain-Specific
- Enhance the relevant domain section (code, writing, business)
- Add domain-specific examples
- Include specialized terminology

## Next Steps

- Read `examples.md` for more interaction examples
- Check `CONTRIBUTING.md` to improve RudeGPT
- Share your experience and feedback

## Support

Having issues?
1. Check the `examples.md` file for expected behavior
2. Review `gpt-config.md` for configuration details
3. Open an issue on GitHub

---

Now go forth and get some brutally honest feedback!
