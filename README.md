# investpy-base

I'll try to upload partial data for local testing but will only provide full set of data for sectors 'Pharmaceuticals' and 'Electricity' up to 8th Feb 2020.

## Known issues
1. I've attempted to remove weekends using `rangebreak` but it's not working. Possible issue: https://github.com/plotly/dash/issues/1196
2. `rangeslider` is used to provide options to view at different timeframes but range of y-axis may be unfavourable.
3. Should confirm latest data by matching dates instead of using e.g `iloc[-1]['Volume']`.
4. Margins of top bar can be improved
5. Detect increase or decrease from previous value, use red/green to indicate change direction.