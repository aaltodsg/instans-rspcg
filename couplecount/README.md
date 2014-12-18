
## Couplecount

_Note: To run the example, [INSTANS](https://github.com/aaltodsg/instans) needs to be [installed](https://github.com/aaltodsg/instans/wiki). It is also assumed that
the $INSTANS_HOME environment variable points to the INSTANS root directory._

The example has been explained [here](https://www.w3.org/community/rsp/wiki/Example_of_RSP-QL_query). The INSTANS version does not
calculate system-wide time windows, but otherwise produces the same
solutions.

A test can be run by entering:

`$ ./couplecount.sh`

The related files are:

* _queries/couplecount_basic_v1.rq_: The set of queries.
* _input/pois.ttl_: A list of points of interest classified by type.
* _input/social.ttl_: A social network with person-a knows person-b
  types of relationships.
* _input/stream1.ttl_: A stream of sample events.

