## Legato 0.0.3 ##

*   Merged branch oauth-1-support

      If you pass on an OAuth 1 (not 2, the default) token from the OAuth gem, Legato will use that.
      Support for OAuth 2 is greater than OAuth 1 because of subtle and annoying differences in their operation.

    *Tony Pitale*

## Legato 0.0.2 ##

*   Specify request fields to slim down content returned

      Include request fields columnHeaders/name, rows, totalResults, totalsForAllResults

    *Patrick Roby*

*   Add total results and totals_for_all_results to Query#load

    *Patrick Roby*

*   Change :order to :sort to match GA

    *Patrick Roby*

*   Add webPropertyId to Management::Profile

    *Patrick Roby*

*   Allow explicitly setting the join character on filters

    *Tony Pitale*

*   1.8.7 Support

    *Tony Pitale*

## Legato 0.0.1 ##

*   Initial implementation

    *Tony Pitale*