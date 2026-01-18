# Master-Time-Series-Analysis-and-Forecasting-with-Python-2026-Notes
This Repository contains my "Master Time Series Analysis and Forecasting with Python 2026" Course Notes from Udemy

**I) Time Series Analysis and Forecasting with Python**

**A) Time Series Analysis and Forecasting with Python**

**B) Course Introduction**

**C) Overview of the AI Time Series Assistant**

**D) Diogo's Introduction and Background**

**E) Unlimited Updates and Enhancements 2026**

**II) Section 2: Part 1 - Time Series Analysis**

**A) Time Series Analysis Overview**

**III) Section 3: Python for Time Series Analysis**

**A) Game Plan for Python for Time Series Analysis**

**B) **Load and Explore Data****

**C) Subsetting Stores and Basic Aggregations**

**D) Working with Datetime Index and Weekday Patterns**

**E) Standardizing Sales and Comparing Weekday Patters**

**F) Analyzing Sales on a Specific Weekday**

**G) Removing Outliers and Re-Assessing Intra-Week Seasonality**

**H) Analyzing the Impact of Promotions**




# **I) Time Series Analysis and Forecasting with Python**

# **A) Time Series Analysis and Forecasting with Python**

You ever feel like you're the keto vanilla ice cream of the business world?
Boring and disappointing that you're still doing forecasting the old way like a rolled ice cream when everyone now talks about a -- pistachio flavor?

Well, not anymore.

In this course, you'll be at the forefront of time series forecasting from time series analysis and diving deep into advanced forecasting models.
I'll guide you through every step.

You will cover everything from simple exponential smoothing to cutting edge models like LinkedIn, Silver Kite, Prophet, and Amazon Cronos.

Think you're just a small fish in a big pond?

Let's change that with hands on exercise, real world challenges, and capstone projects.
You won't just learn, you'll do.

Revenues.
Electricity.
People.
Temperatures.

If it moves, we predict.

By the end you'll be forecasting trends with the precision of a sniper, turning your yearly revenue into your monthly income.

And who's going to lead you through this journey?

Well.

Hi.

I'm Diogo, your guide, mentor, and now ice cream coach with years of experience in data science and a passion for turning complex concepts into actionable insights.

I practice what I preach.

Jump in and let's make this year your breakthrough.

This is your moment.

Make it count.

Enroll now and let's crush it together.

# **B) Course Introduction**

I'm very happy that you picked this course to learn time series analysis.
It's the fifth year that this course has been live, and I truly think it's the most complete out there.

And there's absolutely no video that were in the, let’s say, first two editions that are currently live now.
So it’s currently always, always updating.

What I want to show you throughout this video is every single change since the 2025 version to now, the 2026 version.
This walkthrough will help you understand exactly what has improved and why it matters.

The key changes start with much crisper videos.
I really try to make sure that all videos are shorter and more focused.

We also now have deeper explanations and better explanations overall.
The goal is not just speed, but clarity.

Coding is now done with AI in, I think, most of the videos by now.
This allows us to spend more time looking at documentation and understanding what is what and why we are doing it, without the hassle of writing all the code manually.

Of course, we are very critical about it.
In the end, the code used is the one that I like, not necessarily the one that, in our case, Jamie and I are told to use.

We also add new projects and topics based on popular demand.
So the bottom line is, if you want something, tell me.

If there are a few people that want the same thing, I’ll make it happen.
And that’s a promise.

I also introduced an AI assistant.
You now have a time series analysis assistant that you can take anywhere with you and use in your job or during interviews.

This is a print screen of the assistant.
All the materials of the course are there—honestly, everything is there.

It’s just about asking the right questions.
And the assistant responds, I think, in my tone.

So if you like the way I talk or the way I use words, you’re going to like this as well.

Now, let’s look at what the course was in 2025.
At that time, we had five parts.

These were time series analysis, modern time series models and forecasting, deep learning for time series, and advanced content for time series.
We also had a Python appendix.

The Python appendix was for those who were not very familiar with Python but still wanted to learn.
There was a crash course at the end.

These were all the sections that were available back then.
I don’t want to spend too much time listing them, but they’re all there.

The question then becomes: what did we change?
This is where the remakes come in.

One important highlight is a new part called the Time Series Graveyard.
These are techniques that existed before but have not been updated by the teams maintaining them.

That’s why I’m calling it the graveyard.
This section also exists because of your requests.

In the past, I removed some sections.
Some people later asked if they could still access them.

So now, instead of removing them completely, they live in the Time Series Graveyard.
I wouldn’t advise you to focus on them, but it’s your choice.

This section includes everything that was either remade or added.
Anything marked as new represents a true addition.

We added new practice exercises for time series analysis.
We also added new intermittent forecasting and classification for time series.

For sections that are not marked as new, their Python tutorials were fully remade.
This was necessary because new changes in the libraries required updates.

As a result, the course is now 100% up to date.
Nothing is outdated or obsolete.

This is how the 2026 version of the course is now organized.
It consists of six parts.

These are time series analysis, modern time series, deep learning, advanced content, the graveyard, and the Python appendix.

The course is also now split between sections and projects or exercises.
Depending on your goals, you can choose how deep you want to go.

If you want structured learning, you can focus on the sections.
If you want to build a portfolio, you’ll find plenty of projects and exercises.

One important thing to note is that the course is actually shorter than it was one year ago.
This is despite having a lot of new content.

The reason is simple: the videos are crisper and better edited.
Using AI for coding also makes learning much faster.

This creates a smoother and more efficient learning experience.
That’s something I’m genuinely excited about.

The 2026 version is live.
So let’s get started.

# **C) Overview of the AI Time Series Assistant**

In the previous lecture, I gave you a link to the AI time series assistant, and in this video I want to give you a brief introduction to it. I’m going to call this version one of the assistant. I focused a lot on getting the core functionalities and the architecture right so that I can build on it later. There are quite a few things that could still be improved, and that’s exactly what I’m looking for when you share your feedback.

In this video, I want to introduce what it can do, what it cannot do, and the other actions available. It’s always going to be a time series course assistant, and it has a collapsible bar where you can see its capabilities, the core topics it covers, and also what it cannot do. For example, it cannot give medical advice, it cannot run code, and it cannot browse the web. You’ll also see a “ready to predict the future” message and some initial information explaining what it can and cannot do.

Let’s say we enter a message, for instance, “explain time series analysis,” and then click on send. You’ll notice that it shows when it’s thinking, both in the chat itself and at the top, where it indicates that it’s running. This assistant is going to complement the AI assistant from Udemy. There are a few things they have in common, especially when it comes to the videos themselves, because both have access to the transcripts. In fact, everything from the Udemy AI assistant comes from those transcripts, so if you want something specific to a given lecture, that’s where it’s useful.

For example, if you want a summary of a lecture, the Udemy assistant is very good because everything is directly linked to your current video. However, this time series assistant is not linked to your current video experience, so that’s one area where Udemy’s assistant is better. On the other hand, this assistant has some clear advantages. First, it’s always going to be up to date. For instance, we’re currently using GPT-5 already, whereas the Udemy assistant, based on things like its use of words such as “delve,” still feels very much like GPT-4.

At the same time, this assistant has all the course material loaded into it. That includes all the Python code, all the PDFs, and everything else from the course. So if you want something really tailored to the course—especially things you want to use, reuse, and take into your professional life—this is the one to use. It’s also not really tied to Udemy, which means you can keep it open and ask questions while you’re working on your own projects.

This tool is meant for you to use and reuse. Of course, there are many things that can still be improved. There’s an option to give feedback, and while I’d obviously love it if you love it, what I really care about is that you share what you like and what you would improve. This could be things like the colors, the layout, or any other aspect. Again, this is version one.

If you’ve been with the course for a long time—especially since the course originally dates back to 2021—you know that I’m always improving it. There will be a version two, version three, and so on, because I’m very focused on making this the best course possible.

While you’re here, you can also ask things like, “Give me the code for exponential smoothing,” press control-enter, and the assistant will think and respond. Alongside this, I want to emphasize that the feedback section is really important. Sometimes people ask for personal help through the feedback, but I can’t help you that way. If you need my help directly, you should always use the Q&A section. I answer questions there almost every day—there’s maybe one day a month when I don’t check it.

The Q&A is always the best way to reach out to me. I do gather feedback from this tool, but I don’t check feedback every day. I usually review it weekly or monthly, make sure everything is working, and then act on it after a couple of months to improve the tool. One example of feedback is that the Udemy assistant allows you to add images, which is really cool, whereas this one currently cannot. That’s something to keep in mind for future improvements.

You’ll also find all the code used in the course here. This is the same code we use throughout the course, and it should always be up to date because it reflects the latest course materials. If you ever find any issues, please let me know, because sometimes it can produce hallucinations, which I can’t fully control.

If at any point you don’t want to continue a conversation and you want to start fresh, you can reset the conversation. That will start a new session. Everything here is session-based only—there’s no database in the backend, and nothing is stored.

If this is something you love and use a lot, there’s an option to donate. This is completely optional, but I want to be transparent that this tool does cost money to run. The cost for one to ten people is basically nothing, but when you get to thousands of users, it becomes more significant. So if it genuinely makes a difference in your life, you can support it, but again, it’s absolutely optional.

At the end of the day, this is yours. Even if you hate me, you can bookmark it. There’s no login, and it’s an open tool that you can use and reuse. It’s here for you to keep. I personally find it very cool when people use my work, so if you do use it, let me know.

# **D) Diogo's Introduction and Background**

Hi there, I’m Diogo, and I’m thrilled to welcome you to this course. Before we get started, let me share a bit about myself so you know who’s guiding you through this journey.

I hold a Master of Science in Management from ESMT Berlin, one of the top business schools in Europe, where I specialized in business and analytics. My professional career has been centered around using data to solve complex business challenges. I’ve worked on projects ranging from sales planning involving billions of euros to A/B tests where companies had to invest hundreds of thousands of euros. I’ve truly been around the block and have had a lot of hands-on experience.

Beyond teaching, I’m also a startup founder. My company, which you can find at Join Betacom, aims to leverage the power of data to help restaurants around the world. We analyze vast amounts of data to provide actionable insights, such as optimizing menus or determining the best pricing strategies for their products. And if you’re interested in my startup, feel free to reach out and drop me a line.

I’m here not just to teach, but to genuinely support your learning journey. If at any point you feel that this course isn’t the right fit for you, don’t hesitate to reach out. I’m more than happy to guide you toward a learning path that suits you best, even if that means recommending other resources or courses that better align with your learning style.

Before we wrap up, I’d like to extend a personal invitation for you to connect with me on LinkedIn. Simply search for Diogo Alves de Rezende, and let’s keep the conversation going. I’m always eager to engage with my students and grow our professional networks together.

Once you complete this course and earn your certificate, I encourage you to share it on LinkedIn. I make it a point to repost these achievements and celebrate your success, just as I’ve done for many of my students. It’s a great way to gain visibility and start building your professional reputation in the business and analytics community.

My goal is for you to succeed and feel empowered to make a real impact. Whether you’re here to advance your career, pivot into a new industry, or innovate within your own business or company, I’m excited to help you achieve those dreams.

# **E) Unlimited Updates and Enhancements 2026**

Hey, before we start, let me talk about the current status of this course and what’s coming next.

All the content you’re about to dive into has been pre-checked and updated to ensure it’s relevant and accurate for 2026. I know how fast technology evolves, and that’s why I’m committed to keeping this course up to date with the latest developments and insights, so you can stay ahead of the curve.

That said, in a world that’s constantly changing, there’s always a chance that something might slip through the cracks. If you notice any outdated information or anything that doesn’t feel quite right, please don’t hesitate to let me know. Your input is invaluable in maintaining the quality and relevance of this course.

In addition, if there’s any specific content or material that you’d like to see added, I’d love to hear from you. Your suggestions help shape the future of this course.

In the next lecture, I’ll share a form where you can report anything that’s incorrect, offer suggestions, or request additional resources. This course is a collaborative journey, and your feedback plays a key role in making it the best it can be.

Thank you for being an active part of this learning community. I’ll see you in the next video.

# **II) Section 2: Part 1 - Time Series Analysis**

# **A) Time Series Analysis Overview**

Welcome to the time series analysis part of the course. This is where you take your data skills to the next level, learning how to make your data work for you and predict future trends with accuracy. Let’s get started.

Have you ever wondered how companies like Amazon and Netflix always seem to know what’s coming next? It all comes down to mastering time series forecasting. By the end of this section, you’ll be applying the same techniques to your own business and career, turning raw data into accurate, actionable predictions.

We’ll begin by understanding what time series data is and why it plays such a critical role in forecasting. You’ll work with real-world data in Python and set up all the essential tools needed for time series analysis. This foundation will allow you to build robust models and generate precise predictions.

Before forecasting effectively, it’s essential to know your data inside out. You’ll perform exploratory data analysis to uncover hidden patterns and structures in your time series. Through visualization and data manipulation techniques, you’ll learn how to interpret your data and prepare it properly for forecasting.

You may notice that certain trends repeat over time—this is known as seasonality. You’ll learn how to decompose your data into seasonal, trend, and residual components. This breakdown will help you model your data more accurately and significantly improve your predictions.

Understanding how past data points influence future values is another key concept. You’ll explore autocorrelation and partial autocorrelation to measure these relationships. This knowledge is essential for selecting, tuning, and validating your forecasting models.

Next, we’ll dive into a range of forecasting techniques. You’ll start with simple exponential smoothing, which works well for short-term predictions. From there, you’ll move on to the Holt-Winters method to handle seasonality. You’ll also work with more advanced models such as ARIMA and SARIMAX to capture complex patterns in time series data.

Imagine being able to predict stock prices or customer demand with confidence. You’ll develop these skills through hands-on exercises and real-world challenges. This section is not just about theory—it’s about applying these techniques to real data and understanding their results.

You’ll also explore what happens when forecasting goes wrong. By studying real case studies where predictions missed the mark, you’ll learn to recognize common pitfalls and improve your forecasting approach.

Finally, you’ll bring everything together in a capstone project focused on forecasting airline miles. You’ll prepare the data, build forecasting models, and evaluate their performance. By the end of this project, you’ll have a strong, practical example of your forecasting skills to showcase professionally.

You’re not just learning how to forecast—you’re mastering a powerful skill that can transform your career. See you in the next video.

# **III) Section 3: Python for Time Series Analysis**

# **A) Game Plan for Python for Time Series Analysis**

In this section, you are going to use Python as a tool to understand time series. This is not really an academic exercise. We’re going to work with real data, real questions, and we’re going to aim for real decisions.

We’re going to move fast, stay focused, and build intuition step by step. The goal is to truly understand time series, not just in theory, but in practice.

I can tell you already that you don’t need to be a master of Python. You only need enough to slice data, spot patterns, test ideas, and eventually explain what’s actually going on in the business. That’s really the core objective here.

If you already feel comfortable with Python, that’s great—you’ll be sharpening your instincts. If, however, you’re rusty or starting fresh, don’t worry. There’s a full Python crash course at the end of this course where you can practice more or even start from zero at your own pace.

# **B) **Load and Explore Data****

You are going to find this inside Python for Time Series, which itself is inside Time Series Analysis, and then Python for Time Series Analysis. There, you will find a file called lab starter one.

And here we go.

So we are here. I need to reconnect. This is basically taking our script and saying, “Hey, this is live.” Then I would mount the drive here. Of course, if you’re not using Google Colab, you don’t need to do this step. This is just for those who are using it. Whichever workspace you’re using, just go for it.

In case you’re using Colab, let me show you. You go to Drive → My Drive. This is so that you get the path. Inside My Drive, you’ll find Python Time Series Forecasting. Then inside Time Series Analysis, you will find Python for Time Series Analysis. I will copy the path here. Here we go. Control. Of course, nothing changes, and here we go.

So this is the part where I do this with you. Of course, it’s very specific for Colab. And now we can go.

Task number one is to import the pandas library. All right, let’s do this. Import the pandas library. It’s very simple:
import pandas as pd.

So pandas is the library, and pd is the short form that we are going to call. Cool. Shift + Enter. Task number one is done.

Then task number two is to load the train.csv file into a DataFrame called df, and preview the first rows. You’re going to find the dataset in your materials. It’s a very cool dataset. It has a lot of stores, the day of the week, and it’s a very rich dataset for us to explore and practice some Python.

And here we go. DataFrame. So I’m going to call it dataframe = pandas.read_csv("train.csv"). There was an extra dot here, so let me remove it.

Then I do dataframe.head(). In case you’re using the Jupyter functions of Colab or whichever it is, the comments are going to give quite a few things away. I would always encourage you to double-check and make sure that whatever you’re doing makes sense. In the end, or in case you can, just try to do it on your own. That’s always the best way to practice.

Of course, when you’re actually doing the work, go for it. Go fast. As for practicing, doing it yourself is a tiny bit better.

Now we look at the dataset. We have store, day of week, date, sales, customers, whether it was open, whether there was a promo, whether we have a state holiday, and a school holiday.

The dataset is from a very well-known store, Rossmann. It’s all in German, but it’s basically something that sells things like cleaning products, beauty products, and so on. And of course, at least in Germany, there’s something very specific: some stores are closed on Sunday. That’s something we need to consider.

But if we look at it here, let’s look at something. We see a dtype warning for column seven. Remember, Python indexing starts at zero, so we have columns 0, 1, 2, 3, 4, 5, 6, 7. So the state holiday column has something weird going on.

We can specify the dtype option on import or set low_memory=False. This is clearly something we need to investigate. So I’d say the first step is to look at information about the DataFrame.

To do that, we use dataframe.info(). This provides some information. We can see that, for instance, state_holiday is currently an object. And when we look at it, it has zeros, but it’s an object type, which means it has characters or letters inside. That’s something we definitely need to investigate.

This leads us to task number four. We’re going to print the unique values in state_holiday and their counts.

The way we do this is dataframe["state_holiday"].value_counts(). And we should get something. If you’re not using a notebook style environment, you’d have to use print. I personally have a big preference for notebook styles because of the input-output flow—it’s much easier to explore data this way.

So let’s remove the print because this looks way nicer. We can see that we have a zero, and then we have a different type of zero, and then we have A, B, and C. There is something odd here.

I’m going to assume that A, B, and C are types of holidays, but these two different zeros suggest that something went wrong during data entry. That’s how I’d interpret this right now.

This leads us to task number five. We are going to binarize this set. Instead of having zero, zero, A, B, and C, we’re going to have just zero and one. The A, B, and C values will become ones, and both types of zero will become zeros.

Let’s do this. I’ve found that the simplest way is to use the following format. We take dataframe["state_holiday"] and use .isin(["A", "B", "C"]). Then we convert this to integers using .astype(int). This makes sure that whatever matches A, B, or C becomes a one.

I find this approach intuitive because we’re simply saying whether the value is in A, B, or C. The astype part may not be intuitive at first, but it’s a very simple way to convert booleans into zeros and ones.

Cool. Then we run this and replace the column in the same variable. There was one extra quote there, so we remove it.

Now let’s check again by running value_counts() on state_holiday, just like before. Control + Enter, and here we go. We now only have zeros and ones.

# **C) Subsetting Stores and Basic Aggregations**

When we look at the data, we can see that we have stores, and because there are a lot of entries, it’s not immediately clear how many stores we actually have. It’s usually very helpful to understand the structure of the data you’re analyzing.

So we’re going to count this. Let’s make it nice and readable by printing it using an f-string. We print something like: “There are” and then the length of dataframe.store.unique(), followed by “stores”.

When we run this, we see that there are 1,115 stores. That’s quite a lot for the sake of our analysis.

As we start exploring the data or even doing data visualization, visualizing 1,115 stores is simply not reasonable. So there are two things we’re going to do. First, we’re going to randomize a subset to see how things work. Second, we’re going to simplify our analysis from here on out.

What we’re going to do is subset the data to ten random stores, using a random seed of 1502, and then store the result. Let’s do this.

We start with the original DataFrame and sample from the store column. Step by step, we first sample ten stores. When we run this, you’ll notice that every time we run it, the results are the same. That’s because we set a random state.

The random state makes sure that the results I get and the results you get are the same. It doesn’t matter how many times we run it. If you change the random state, the stores will change, but as long as we keep it at 1502, the output remains consistent.

So now that we have these ten stores, we take the DataFrame and filter it. We go to the store column and use isin() to check whether each row belongs to one of these selected stores. When we run this, we get a series of booleans—True and False.

The next step is to use this boolean mask to retrieve only the rows where the value is True. This tells the DataFrame to keep only the rows corresponding to those ten stores. When we do this, we can see stores like 24, 47, and others appearing in the filtered data.

At this point, we want to store this result. So we save it as dataframe_ten. We can quickly preview it to confirm everything looks correct.

One important best practice here is to use .copy(). This ensures that we’re working with a separate copy of the data and that any modifications we make won’t unintentionally affect the original DataFrame. This is just good hygiene when working with pandas.

Now that dataframe_ten is properly set up, we can move on.

Task number three is to compute the mean sales for each of the ten stores and sort them in descending order. Let’s do this.

We take dataframe_ten, group it by store, then select the sales column and compute the mean. Once we have the result, we sort the values in descending order.

When we look at the output, it’s not immediately obvious which store is the biggest just by scanning the numbers, so sorting helps. After sorting, we can clearly see that store number 4 has the highest average sales, while store 794 has the lowest.

There’s quite a big difference here—roughly a threefold difference in average sales. And remember, this is just within our subset of ten stores.

Now, one last thing that I find particularly interesting is the following: for each store, we want to find the row corresponding to the day with the all-time highest sales.

In other words, we want to know which specific day each store achieved its maximum sales.

To do this, we take dataframe_ten, group by store, and focus on the sales column. Instead of computing the mean, we now use idxmax(), which gives us the index of the row where sales were highest for each store. We could also look at idxmin() if we wanted the worst day.

Once we have this, we can optionally sort the results in descending order to see the biggest peaks first.

When we inspect the output, we see something remarkable. For example, store 864, which averages around 3.5K in sales, had one day where sales were close to one million. That’s roughly 300 times its average daily sales, which is absolutely insane.

# **D) Working with Datetime Index and Weekday Patterns**

Task number one is to set the date column as the index, and then preview the first rows.

To give a bit of insight here, when we work with time series data, we care about time. Setting time as the index enables us to manipulate the data in a much easier and more natural way. This is especially important for visualization, because Python then understands that we are dealing with data evolving over time. Without this, Python doesn’t really know that the data is temporal, and I’ll show you that in a moment.

For now, we set the date column as the index. The way we do this is by using dataframe_ten.set_index("date", inplace=True).

Let’s preview a few rows to see what we get. We can see that the date is now shown in a consistent format. That looks good.

But now let’s look at what Python actually thinks about our date column. If we go back and inspect the information, we see that the date is still an object. An object means characters or strings, not a real date.

So we inspect dataframe_ten.index. When we look at it, we see that it has a start, but it’s still considered an object. The name is “date”, but that name itself is meaningless—it’s just a label.

What we need to do is convert this into a proper datetime object. To do that, we use pandas and apply to_datetime on the index. Once we run this, Python now understands that this index represents dates.

At this point, Python knows that we’re working with time, and this allows us to properly explore and manipulate the data from a time series perspective.

Cool.

Now let’s look at something interesting. Even though we’re not heavily using the index yet, a useful exercise is to compute the average sales per day and per store.

Let’s do this.

We take dataframe_ten and use groupby. At this point, you can probably already see how relevant grouping is. We group by day of week and by store. Then we select the sales column and compute the mean.

Here we go.

Now, I know—I know—it’s not very easy to interpret this output just by looking at the table. That’s fine. That’s going to be addressed in task number four.

Before moving on, I want to highlight something important. Instead of using the existing day_of_week column, we could have used dataframe_ten.index.dayofweek, and the result would be exactly the same. In our case, the day-of-week variable already exists, which makes things easier.

But when you work with time series data, you can create all sorts of time-based variables directly from the index—day of week, month, year, and so on. This makes feature engineering very powerful and very simple once your index is properly set.

All right.

So now we move on to visualization.

We want to visualize the average sales per weekday and per store using a line plot.

The simplest way to do this is to reuse the code we already have. I’m a big fan of reusing code whenever possible.

The first thing we need to do is unstack the grouped result. Once we unstack, we can already see that this becomes easier to compare across weekdays—0, 1, 2, 3, and so on. Day 6 corresponds to Sunday.

Since we’re dealing with Germany, this makes sense because many stores are closed on Sundays. Still, even with this structure, it’s not very easy to visualize just by looking at numbers.

So the next step is to call .plot().

When we do that, the visualization becomes much clearer. Now we can actually see the patterns.

Looking at the plot, one thing immediately stands out. All stores have zero sales on Sunday except for one. This is something interesting and consistent with what we saw in the table.

However, there’s another issue. The magnitude of sales differs a lot between stores. Some stores reach sales around 10,000, while others are much lower. This makes comparisons tricky, because the scale dominates the visualization.

And this is where the exercise really starts.

I want you to start thinking about this: when we want to understand how sales evolve during the week, we’re essentially looking at a seasonal pattern. To truly compare these patterns across stores, we should also start thinking about standardizing the data.

# **E) Standardizing Sales and Comparing Weekday Patters**

In order to properly compare behavior across different stores, we need to standardize the data. Standardization ensures that there is a common denominator among the stores, so that we are truly comparing apples with apples.

The standardization formula itself is very straightforward. It works as follows: we take the value, subtract the average, and divide by the standard deviation. This is the classic z-score formulation.

So this is step one. The main challenges here are twofold. First, we need to build a function. This is a very standard Python task and a great way to practice writing functions. Second, we need to apply this function correctly to our data, making sure that we zoom in on each store individually. In other words, we want to compute the mean and standard deviation per store and standardize sales within each store.

This brings us to task number one.

We need to define a function that standardizes a numeric series using z-scores, meaning value minus mean divided by standard deviation. Let’s do this.

We start by defining a function called standardize, and we pass a series as the input. Inside the function, we return the series minus the series mean, divided by the series standard deviation. This is very straightforward.

Now that the function is defined, we need to apply it to our data.

What we need to do is take our DataFrame and group it by store. This ensures that we are focusing on one store at a time. Then we focus on the KPI we care about, which is sales.

When we do this, we group by store, select sales, and apply a transformation using our standardize function. At first, it may show as a generic grouped series because we haven’t applied the transformation yet. But once we apply transform(standardize), the values are standardized per store.

After running this, we can see that the values are now standardized. This allows us to really work with and compare patterns across stores much more easily.

Recall that standardized values are centered around zero, and most values typically lie between -2 and 2. This makes interpretation and comparison much more intuitive.

This leads us to task number three. But before we do that, we need to store the standardized values.

We assign the standardized sales back into our DataFrame using .loc across all rows, and we create a new column called sales_standardized. The name “STD” here refers both to standard deviation and to the normalization itself.

Once we run this, the new column is created. We can quickly preview a few rows using .head() to confirm that everything looks correct.

Now we move on to computing the mean of the standardized sales.

We take dataframe_ten and group by day of week and store. Then we select the sales_standardized column and compute the mean. This gives us the average standardized sales per weekday and per store.

This naturally leads us to task number four.

We take the result, unstack it, and then plot it. This allows us to visualize the standardized weekday patterns much more clearly.

However, there are a few issues here. Nine out of ten stores have no sales on day seven, which is Sunday. This completely skews the visualization. From an analysis perspective, this is not ideal because zeros don’t really carry meaningful information in this context.

One thing that clearly stands out is the brown series, store 353. It shows extremely strong seasonality on Sundays. That makes sense, because if most other stores are closed, this store benefits disproportionately.

This is something we can infer from the data.

If we look at the other series, we see a different pattern. Sales tend to decrease day by day until Saturday, showing a clear weekday seasonality. That’s one conclusion we can draw.

At the same time, Sunday completely distorts the picture and makes it difficult to analyze the remaining patterns properly. We clearly need to clean this up further.

Still, let’s continue exploring.

Let’s take a closer look at Sundays specifically. Are stores always closed? Is there even a single Sunday where some of them are open? The same question applies to the other stores as well.

These are things we can visualize, explore, and then use to draw our own conclusions.

# **F) Analyzing Sales on a Specific Weekday**

I have to say, I only listed one task here, but this could have been done in multiple ways. What we need to do is filter the data for day seven and then visualize it. So this will be step number one and step number two at the same time.

First, let’s import what we need for visualization. We import matplotlib.pyplot as plt. That’s step number one.

Next, we create a new DataFrame called dataframe_d7. We start from dataframe_ten. There are many ways to do this. One way is to filter where the day of the week is seven and then make a copy. That’s one valid approach.

Another option would have been to use the index directly, since we’ve already set it to datetime. That’s another possibility. In this case, we’ll stick with using the existing variable and filtering based on the day of the week.

Now we move on to plotting.

We start by creating a figure using plt.figure(). We set the figure size to 12 by 6, which is a fairly standard size.

Next, we loop through the data. For each store and its corresponding data in dataframe_d7 grouped by store, we plot a line. We plot the date, which is stored in the DataFrame index, on the x-axis, and sales on the y-axis. For each line, we set the label using an f-string so that it shows the store number.

This loop allows us to plot each store’s Sunday sales on the same chart.

We close the parentheses and then display the plot. This is already enough to generate the visualization. It’s also a nice introduction to matplotlib if you’ve never used it before, because it shows the basic structure of creating a figure, plotting data, and labeling it.

Now, here’s a cool thing that you might or might not have noticed. Let’s quickly look at dataframe_d7 itself. You’ll see that the earliest dates are from 2015, and the later dates are from 2013. In other words, the data is reversed.

However, because Python knows that we’re dealing with dates, this doesn’t matter at all. When we plot the data, everything is automatically ordered correctly along the time axis.

That was just a quick side note.

Now let’s clean up the plot a bit. We add a title, “Sales on Sunday”. We label the axes with date and sales. We also add a legend so that we can identify each store.

I also like to add plt.tight_layout(). This usually tidies things up a bit and makes the plot easier to read, which I personally appreciate.

When we look at the plot, I feel it’s a bit too tall, so we reduce the figure height from 6 to 5. That small adjustment makes it look better.

Now, what do we see?

We see that every single store except one is always closed on Sundays. There are no exceptions at all. This tells us that by including Sundays in our analysis, we’re potentially introducing noise—especially when we standardize the data.

For store 353, there is one Sunday where the store was closed, which explains a drop. But aside from that, this store has recorded sales on every single Sunday, and those sales are growing over time. That’s definitely interesting to observe.

And that’s it.

This is how we do a quick visualization to explore a specific pattern in the data. I would say this exercise is on the more difficult side, because it includes a for-loop and multiple steps. But if you understand this, you’ll be able to handle virtually every visualization throughout this course.

# **G) Removing Outliers and Re-Assessing Intra-Week Seasonality**

Our conclusion so far is that we clearly have store 353, which behaves very differently from the others. There’s really no point in comparing it directly with the rest. At the same time, we also have day seven, which is Sunday, and this day is kind of “poisoning” our data because it introduces a lot of noise.

Because of this, task number one is to remove all observations for day of week seven and for store 353. Doing this will give us a much cleaner DataFrame, allowing us to continue exploring seasonality in a more meaningful way.

Cool, let’s do this.

We start from dataframe_ten. We want to keep only the rows where the day of week is not seven and the store is not 353. Since we have two conditions, we need to combine them.

First, we filter dataframe_ten where the day of week is not equal to seven. Then, we add a second condition where the store is not equal to 353. Finally, we make a copy of the result to avoid any unwanted side effects.

We store the result in a new DataFrame called dataframe_clean.

Once that’s done, we can take a quick look using .head(). This preview doesn’t show anything dramatic, because we’ve removed rows rather than added new ones. The main purpose here is simply to confirm that we still have data and that the operation worked as expected.

Now that we have a clean DataFrame, the next step is to re-standardize the sales column within each store, but this time using dataframe_clean.

We essentially repeat the same process as before. We take the sales column, group by store, and apply the standardization transformation. The result is stored again in the sales_standardized column.

If we preview a few rows using .head(), we can immediately see that the standardized values have changed. For example, values that were previously around 1.5 and 1.1 are now closer to 1.65 and 1.16. This makes sense, because we’ve changed the underlying data by removing Sundays and the outlier store.

This brings us to task number three.

We now take dataframe_clean and group it by day of week and store. Then we select the sales_standardized column and compute the mean. This gives us the average standardized sales per weekday and per store, using the cleaned data.

As mentioned earlier, we can store this result. Let’s call it intra_week.

Now we move on to task number four, which is visualization.

To visualize the intra-week seasonality, we take intra_week, unstack it, and then plot it. Compared to before, the view is much clearer. Earlier, everything almost looked like a straight line. Now we can actually see meaningful differences and patterns.

We can also customize the plot directly within pandas. For example, we can set the figure size to 12 by 6, add a title such as “Intra-week Seasonality of Standardized Sales”, and adjust the layout. If we want to remove or fine-tune certain axes, we can do that as well.

Reducing the figure height slightly—from 6 to 5—makes the visualization a bit cleaner and easier to read.

Now let’s interpret what we see.

There’s one store, store 267, that shows very strong Saturday performance, which is quite unique. In general, Thursday to Saturday seem to be the strongest days for most stores. From Monday to Tuesday to Wednesday, sales tend to decrease, and then there appears to be some stabilization.

Overall, Monday is often the strongest day, Saturday the weakest—except for that one store. We also see a general decrease until Wednesday, followed by a flatter pattern for the rest of the week.

One important takeaway here goes beyond just seasonality. This exercise demonstrates the process of time series analysis. We take a sample of data, analyze it, and identify problems. Then we ask questions like: “What’s causing this distortion?” In this case, Sunday was the issue, so we removed it.

Next, we notice a store that behaves completely differently. That store clearly belongs to a different category and should be analyzed separately. Ideally, we would later compare stores that are open on Sundays with those that are not, because they may not be directly comparable.

This is how we move step by step toward insight: analyze, detect anomalies, clean the data, reanalyze, and visualize the results. And ideally, at the end of this process, we present clear visualizations that support our conclusions.

# **H) Analyzing the Impact of Promotions**

One of the most interesting questions—especially in revenue planning or demand planning—is understanding the impact of promotions on revenue. This is something we are going to explore slowly here, just a little bit, from a more data-exploratory perspective.

Let’s start with the first task. We want to compare the average sales on promotion days versus non-promotion days. To do this, we use a function you’re probably already tired of by now: groupby. We group by the promo variable and then compute the mean. This immediately gives us something concrete to compare—average sales when promotions are active versus when they are not.

At this point, you might notice something odd happening, especially if you’re working in Colab. You may realize you’re doing something wrong, or Colab might not be cooperating properly. When that happens, it’s totally fine—and often necessary—to restart the runtime and rerun everything from scratch. That’s exactly what we do here.

After restarting and rerunning the pipeline, we see the results clearly. Average sales on promotion days are around 7991, while on non-promotion days they are around 4.4k. That’s already interesting. Here, I’m intentionally switching back to using the full data frame instead of one of the cleaned or filtered versions from before. For this particular analysis, working with the complete data frame feels more natural and helps illustrate a few additional concepts.

Now we move to task number two. Instead of looking at promotions globally, let’s break this down per store. We want to compare promotion versus non-promotion sales at the store level. To do this, we group by both store and promo, select sales, compute the mean, and then unstack the result. This gives us a table where, for each store, we can directly compare average sales with and without promotions.

We store this result in a new object called promo_uplift. This data structure now contains the mean sales per store, split by promotion status. We can inspect it using .head() or similar methods to confirm everything looks correct.

Task number three is where things get more interesting. For each store, we want to compute the relative uplift in sales during promotion days compared to non-promotion days. The idea is simple: we take the difference between promotional and non-promotional sales and divide it by the non-promotional baseline. In other words, (promo − non_promo) / non_promo.

This relative format is very useful because it puts all stores on a common scale, similar to standardization. Even if stores have very different absolute sales levels, relative uplift allows us to compare them fairly. We compute this relative difference and add it back to our promo_uplift structure. After that, we can again inspect the results to make sure everything looks reasonable.

At this stage, a very natural and insightful question arises: in which stores is promotion actually making a meaningful difference? To answer this, we look for the stores with the largest relative uplift. We take the computed uplift values and use nlargest(5) to identify the top five stores in terms of promotional elasticity.

This reveals some very interesting results. For example, stores like 198 and 607 stand out, and one store—store 108—shows an uplift of around 2.25x. That’s a very significant increase and clearly indicates that promotions are extremely effective in that store.

Task number five is simply the flip side of this analysis. If we can find the highest promotional elasticity, we should also look for the lowest. Using nsmallest(5), we identify the stores where promotions have little to no impact on sales. This immediately raises important business questions: what’s happening in those stores? Why don’t promotions work there?

Of course, there are many possible explanations. There could be other factors we’re not accounting for, such as how often promotions are run, when they are run, or how large they are. Promotions aren’t just a binary yes-or-no variable. They have magnitudes—depth of discount, breadth of products included, and timing over time. These are what we call confounding factors, and they can strongly influence the observed effect of promotions.

Overall, this exercise shows how we can start uncovering meaningful insights step by step using relatively simple exploratory techniques. If you’d like to see more exercises like this—especially ones that dig deeper into real business questions—just let me know, and I’d be very happy to create them for you.
