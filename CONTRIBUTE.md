# Time-machines contributors guide

You may ask yourself, "Well, how did I get here?" And you may ask yourself, "How do I work this?". And you may find yourself behind the wheel of a large automobile. 

<img src="https://github.com/microprediction/timemachines/blob/main/images/talking_heads.jpeg" alt="drawing" width="450"/>

But enough 80's rock. Chances are you're here because you reached out to connect on Linked-In, and you have some manner of time-series or quantitative interest, so I sent you an invite. 

## Vague objective

... and now you find yourself in a conspiracy aimed at upending artisan data science by unleashing a billion little reward-seeking algorithms into a micro-economy, commoditizing repeated quantitative tasks of all kinds. That might be a better idea than waiting for DeepMind to to something, [according to a wise man](https://www.microprediction.com/blog/reward).   

## Specific goals 
Hello, we hope you are interested in helping us create free open short term prediction of anything for anyone, as follows: 

   - Packaging a slew of fully autonomous univariate forecasting functions:
        * With a simple sequence-to-sequence signature ("skaters")
        * Drawing on whatever useful open-source Python packages can be found. 
   - Evaluating them continuously over fresh, live, diverse real-world timeseries in two ways:
        * Computation of [Elo ratings](https://microprediction.github.io/timeseries-elo-ratings/html_leaderboards/overall.html)
        * Incorporation in "crawlers" than operate in real-time and predict time-series at www.microprediction.org where they play this [game](https://www.microprediction.com/blog/intro), and in doing so, provide free high quality short-term prediction to anyone, anywhere, for any reason.
 
Thereby we can address otherwise thorny issues like [defining anomaly detection](https://www.microprediction.com/blog/anomaly) in a way that isn't circular. Part of this involves stacking, composing and otherwise exploiting existing skaters. We'd like to see [Fast Python Timeseries Forecasting](https://www.microprediction.com/blog/fast) become the norm. 

# Contribution Patterns

Little things do help
   - Follow, clap, share, heckle on [medium](https://microprediction.medium.com/), [linked-in](https://www.linkedin.com/company/65109690)
   - Star, fork, watch [timemachines](https://github.com/microprediction/timemachines)

## Running scripts

Contributing compute:
   1. Cut and paste a bash command to drive the default "crawler". See [CONTRIBUTE_COMPUTE_LOCAL_ONE_LINE.md](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_COMPUTE_LOCAL_ONE_LINE.md). Run a Python script directly if you prefer. See [CONTRIBUTE_COMPUTE_LOCAL](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_COMPUTE_LOCAL.md). Or run a Python script on a PythonAnywhere account that drives a "crawler". See [CONTRIBUTE_COMPUTE_PA](
 https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_COMPUTE_PA.md)
   2. Cut and paste a bash command to burn some rare Memorable Unique Identifiers, and donate them. See [CONTRIBUTE_COMPUTE_MUIDS.md](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_COMPUTE_MUIDS.md)
 
 ## Contribution to crawler creation  

   3. Create any kind of Python crawler. Run it. Improve it. Repeat. See the [knowledge center](https://www.microprediction.com/knowledge-center) tutorials.
   4. Create any kind of crawler, not in Python. There's less support for that, but see the [public api](https://www.microprediction.com/public-api) and Google search (for "microprediction client Julia", for example, or "micropredciction client typescript). 

## Contribution to the timemachines package
Open issues:

   5. See [good first issues](https://github.com/microprediction/timemachines/issues)

New package inclusion and approaches

   6. See [CONTRIBUTE_BATCH_STYLE_MODELS](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_BATCH_STYLE_MODELS.md) to add new functionality using non-incremental methods.
   7. See [CONTRIBUTE_ONLINE_STYLE_MODELS](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_ONLINE_STYLE_MODELS.md) to add new functionality using incremental methods.
   
## Contribution of live data
Add live data that feeds the Elo ratings, and live contests too. 

   8. See [CONTRIBUTE_LIVE_DATA.md](https://github.com/microprediction/timemachines/blob/main/CONTRIBUTE_LIVE_DATA.md)

# Friday chats

  - Grab the slack invite from the [knowledge center](https://www.microprediction.com/knowledge-center) or convey your email to me in some way (info@microprediction.com will do)
  - Turn up to one of the informal chats we have every Friday noon EST. 
  - If that timezone is bad, maybe Tue 8pm EST. 
  
But if you are shy that's fine too. I look forward to your pull requests, or seeing you on the leaderboard. Crawling can be completely anonymous, by the way. 
