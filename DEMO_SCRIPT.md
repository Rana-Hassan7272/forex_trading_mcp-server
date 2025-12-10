# Forex Trading Assistant - Demo Script

## 🎬 Video Demo Prompts

Follow this sequence to demonstrate all features. Each section shows a natural conversation flow.

---

## 📋 Section 1: Introduction & First Trade

### Prompt 1: Greeting
**You say:** "Hi, I'm a forex trader. Can you help me track my trades?"

**Expected:** Bot introduces itself as trading assistant and explains capabilities

---

### Prompt 2: Save First Trade (Partial Info)
**You say:** "I just took a new trade. Entry price is 2000, lot size 0.01, my balance is 1000, and it's a BUY trade."

**Expected:** 
- Bot asks for missing important fields (take profit, stop loss)
- Bot asks for optional fields (timeframe, trade style, strategy)
- Shows intelligent field collection

---

### Prompt 3: Complete Trade Details
**You say:** "Take profit is 2010, stop loss is 1990, timeframe is 1h, trade style is scalp, and strategy is SMC."

**Expected:**
- ✅ Trade saved successfully
- Shows trade ID, all details
- Shows calculated risk:reward ratio
- Asks about trade outcome

---

### Prompt 4: Log Trade Result
**You say:** "I won this trade"

**Expected:**
- ✅ Trade logged as WIN
- Shows calculated profit (automatically: $10)
- Shows new balance ($1010)
- Status changed to CLOSED

---

## 📋 Section 2: Multiple Trades & Data Accumulation

### Prompt 5: Save Second Trade (Complete Info)
**You say:** "I took another trade. Entry 2650, lot 0.02, balance 1010, BUY, take profit 2660, stop loss 2645, timeframe 15m, day trade, strategy is trendline."

**Expected:**
- ✅ Trade saved
- Shows trade #2
- Asks about outcome

---

### Prompt 6: Log Loss
**You say:** "I lost this trade"

**Expected:**
- ✅ Trade logged as LOSS
- Shows calculated loss (automatically: -$10)
- Shows new balance ($1000)
- Empathetic response

---

### Prompt 7: Save Third Trade
**You say:** "New trade: entry 3000, lot 0.01, balance 1000, SELL, take profit 2990, stop loss 3010, timeframe 4h, swing trade, strategy is order block."

**Expected:**
- ✅ Trade saved
- Shows trade #3
- Asks about outcome

---

### Prompt 8: Log Win
**You say:** "This one was a win"

**Expected:**
- ✅ Profit calculated: $10
- New balance: $1010

---

## 📋 Section 3: Insights & Analytics

### Prompt 9: General Insights
**You say:** "Show me my trading insights"

**Expected:**
- 📊 Comprehensive analytics:
  - Total trades, win rate
  - Best performing side (BUY/SELL)
  - Best timeframe
  - Best strategy
  - Total profit/loss
  - Average profit per win
  - Risk:reward analysis
  - Best timeframe+strategy combinations

---

### Prompt 10: Specific Insight Request
**You say:** "Which timeframe works best for me?"

**Expected:**
- Shows only timeframe performance data
- Highlights best timeframe
- Win rate by timeframe

---

### Prompt 11: Strategy Performance
**You say:** "What's my best strategy?"

**Expected:**
- Shows strategy performance breakdown
- Win rate by strategy
- Total P/L by strategy

---

### Prompt 12: Date Filtering - Today
**You say:** "How many trades did I take today?"

**Expected:**
- Shows count of today's trades
- Or full insights filtered to today

---

### Prompt 13: Date Filtering - This Week
**You say:** "Show me my performance this week"

**Expected:**
- Insights filtered to this week
- Win rate for this week
- Total P/L for this week

---

## 📋 Section 4: Risk Monitoring

### Prompt 14: Check Risk Alerts
**You say:** "Check for any risk alerts"

**Expected:**
- Shows risk alerts (if any patterns detected)
- Examples: consecutive losses, overtrading, etc.
- Recommendations for each alert

---

### Prompt 15: Simulate Risk Pattern (Optional - if you want to show alerts)
**You say:** "I just lost 3 trades in a row. Check my risk."

**Expected:**
- ⚠️ Alert: "Consecutive losses detected"
- Recommendation to reduce lot size or take a break

---

## 📋 Section 5: Advanced Features

### Prompt 16: Historical Query
**You say:** "How many trades did I take last month?"

**Expected:**
- Shows count or insights for last month
- Demonstrates date awareness

---

### Prompt 17: Trade Details Query
**You say:** "What was my first trade?"

**Expected:**
- Shows details of trade #1
- Entry, TP, SL, outcome, profit/loss

---

### Prompt 18: Performance Comparison
**You say:** "Compare my BUY vs SELL performance"

**Expected:**
- Shows buy_stats vs sell_stats
- Win rate comparison
- Total P/L comparison

---

### Prompt 19: Lot Size Impact
**You say:** "How does lot size affect my performance?"

**Expected:**
- Shows lot_size_impact analysis
- Average lot size for wins vs losses
- Correlation insights

---

## 📋 Section 6: Natural Language Flexibility

### Prompt 20: Casual Language
**You say:** "hey, i took a trade at 2500, lot 0.05, balance 1500, buy, tp 2510, sl 2495"

**Expected:**
- Understands casual/informal language
- Extracts all details correctly
- Saves trade properly

---

### Prompt 21: Partial Information (Test Intelligence)
**You say:** "I want to save a trade. Entry is 1800."

**Expected:**
- Asks for remaining required fields systematically
- Doesn't show "(optional)" labels
- Guides user through all fields

---

### Prompt 22: Quick Status Check
**You say:** "What's my current balance?"

**Expected:**
- Shows latest balance from most recent trade
- Or calculates from last known balance

---

## 📋 Section 7: Error Handling & Edge Cases

### Prompt 23: Invalid Request
**You say:** "What's the weather today?"

**Expected:**
- Politely redirects to trading-related queries
- Suggests available features

---

### Prompt 24: Missing Trade ID
**You say:** "I won my trade"

**Expected:**
- Asks which trade (trade ID)
- Or identifies most recent open trade

---

## 📋 Section 8: Summary & Closing

### Prompt 25: Overall Performance
**You say:** "Give me a summary of my overall trading performance"

**Expected:**
- Comprehensive summary
- Key metrics
- Best practices identified
- Areas for improvement

---

### Prompt 26: Next Steps Suggestion
**You say:** "What should I focus on to improve?"

**Expected:**
- Based on insights, suggests:
  - Best timeframe to focus on
  - Best strategy to use
  - Risk management tips
  - Areas to avoid

---

## 🎯 Quick Demo Flow (5-minute version)

If you want a shorter demo, use these essential prompts:

1. "Hi, I'm a forex trader"
2. "I took a new trade: entry 2000, lot 0.01, balance 1000, BUY, TP 2010, SL 1990, timeframe 1h, scalp, SMC"
3. "I won this trade"
4. "Show me my trading insights"
5. "Which timeframe works best for me?"
6. "Check for risk alerts"
7. "How many trades did I take today?"

---

## 💡 Tips for Video Recording

1. **Start Fresh**: Clear database or use a new user account for clean demo
2. **Speak Clearly**: Pronounce numbers and details clearly
3. **Show Screen**: Make sure chat interface is visible
4. **Pause Between Prompts**: Give bot time to respond
5. **Highlight Features**: 
   - Point out automatic calculations
   - Show how it remembers previous trades
   - Demonstrate date filtering
   - Show risk alerts
6. **Show Persistence**: Refresh browser to show chat history persists
7. **Multiple Users**: Show login feature if time permits

---

## 🎬 Video Structure Suggestion

**Introduction (30 sec)**
- Show the app interface
- Explain what it does

**Section 1: Saving Trades (2 min)**
- Prompts 1-4
- Show intelligent field collection

**Section 2: Logging Results (1 min)**
- Prompts 4, 6, 8
- Show automatic calculations

**Section 3: Getting Insights (2 min)**
- Prompts 9-13
- Show comprehensive analytics
- Show date filtering

**Section 4: Risk Monitoring (1 min)**
- Prompt 14
- Show risk alerts

**Section 5: Advanced Features (1 min)**
- Prompts 16-19
- Show flexibility

**Closing (30 sec)**
- Summary of benefits
- Links to GitHub and FastMCP server

**Total: ~8 minutes**

---

## 📝 Notes

- All prompts are designed to work with your current implementation
- Adjust numbers (entry prices, lot sizes) as needed for realistic demo
- If rate limiting occurs, wait a few seconds between prompts
- The bot should handle all these naturally based on your system prompt

Good luck with your video! 🎥

