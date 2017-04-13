# Clearbit -> Optimizely audience condition... maker

generates the line of JS you need to target certain company 'tags' as [defined by Clearbit](http://support.clearbit.com/article/122-what-values-are-possible-for-company-tags)

## Requirements
A browser

## How to
1. open ClearbitAudienceTags.html in your browser, select tags, copy the snippet
2. create a new Optimizely 'audience'
3. under audience conditions, select 'custom Javascript'
4. paste in the snippet from 1)

## to do
* The last few tags are all "super-tags" that will appear a lot more frequently. This is clearly called out on the [ Clearbit tags documentation](http://support.clearbit.com/article/122-what-values-are-possible-for-company-tags), but functionally they work just like the other tags, so they're not marked in any special way here. I should add a tooltip?

* styling
