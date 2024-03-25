# Canary

Stores the warrant canary for [Michael Standen](https://michael.standen.link).

For information on warrant canarys please see [CanaryTail](https://canarytail.org/).

## Installation

Follow the installation instructions in `lib/canarytail`.

## Validate the canary

To validate the canary, run the following command:

```bash
./lib/canarytail/canarytail canary validate <canary.json>
```

## Create new canary

To create a new canary, run the following command:

```bash
export CANARY_HOME=.
./lib/canarytail/canarytail key new <domain_name>
./lib/canarytail/canarytail canary new <domain_name>
```

## Update the canary

To update the canary, run the following command:

```bash
export CANARY_HOME=.
./lib/canarytail/canarytail canary update <domain_name>
```
