## NG-Redmi Note 11s/13--Search-Hotel filter count changes after reopening filter

## Type
Functional


## Frequency
Every Time

## Severity
High



## Environment
Xiaomi Redmi Note 11S-Android 13, GloMobile, Chrome

## Source
Exploratory

## Action Performed

1. Open the texting link rec3-all.accor.com/booking/en/emblems/hotels/paris-france? compositions=1&dateln=2026-08-24&nights=1

2. Tap on search icon

3. Search for Paris, France

4. Fill dates, rooms and number of guest

5. Tap on search

6. Tap the filter button

7. On the minimum type €20 and on the maximum type €80

8. Tap on the cancel (X) button at the top right corner

9. Tap the filter button

## Expected Result

The system should retain the selected €20-€80 price range and recalculate or display the result count corresponding to that active price range. The displayed count should remain consistent with the number of hotel results available for the selected filtering criteria.

## Actual Result

After opening the Filter page and setting the Minimum Price to €20 and Maximum Price to €80, the action button correctly displays "SHOW 109 RESULTS." After closing the Filter page using the X button and reopening the Filter page, the displayed result count changes to 5 results even though the previously selected price range remains applied. This presents an inconsistent result count to the user for the same filter criteria.
