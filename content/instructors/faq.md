# Instructor FAQ

FAQ from students

## Removing students from PrairieLearn

Q: How can I remove these students from my course (those that have dropped, or registered accidentally)?

A: So the simple answer to your question is that at the moment this functionality doesn't exist. There's an [open GitHub issue](https://github.com/PrairieLearn/PrairieLearn/issues/6039) about it so you can track the progress there if you're interested.

Usually, prevention is the best way to avoid students accidentally enrolling in your course, and I do that in my courses by adding `"hideInEnrollPage": true`, to the `infoCourseInstance.json` file.
For instance, I see that your current course is fully open for any student to enrol in, and is also the first course on the list which is a very tempting target for students.

Something like this access rule should work:

```
{
    "uids": ["firasm@ubc.ca, uid2@ubc.ca, etc@ubc.ca],
    "startDate": "2023-09-01T16:00:00",
    "endDate": "2023-09-01T16:00:01",
}
```