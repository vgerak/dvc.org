# Agenda

In the next few sections we will build a simple natural language processing
(NLP) project from scratch. If you'd like to get the final result or have some
issues along the way, you can download the fully reproducible
[GitHub project](https://github.com/iterative/example-get-started) with:

```dvc
$ git clone https://github.com/iterative/example-get-started
```

Otherwise, bear with us and we will introduce the basic DVC concepts and get to
the same result together!

The idea of the project is a simplified version of the
[Tutorial](/doc/tutorials/deep). It explores the NLP problem of predicting tags
for a given StackOverflow question. For example, we want a classifier that can
predict posts about the Python language by tagging them `python`.

![](/static/img/example-flow-2x.png)

Do not let the NLP nature of the example discourage you from using DVC in other
Data Science areas. There was no strong reason behind picking the NLP area. On
contrary, DVC is designed to be pretty agnostic of frameworks, languages, etc.
If you have data files or datasets and/or you produce other data files, models,
datasets and you want to:

- Capture and save those <abbr>data artifacts</abbr> the same way we capture
  code
- Track and switch between different versions of the data easily
- Be able to answer the question of how data artifacts (e.g. ML models) were
  built in the first place
- Be able to compare them
- Bring best practices to your team and get everyone on the same page

Then you are in a good place! Click the `Next` button below to start ↘
