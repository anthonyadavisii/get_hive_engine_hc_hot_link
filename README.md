# get_hive_engine_hc_hot_link
Python utility generates Hive Connect hot signing links for perform Hive-Engine token transactions

Prerequisites:
Python3 and greater

hivesigner-python-client by @emre [Link](https://github.com/emre/hivesigner-python-client)
Installation:
```
pip install hivesigner
```

Usage:

Import script as module.

```
import get_hive_engine_hc_hot_link

#Example usage
get_hive_engine_hc_hot_link.get_he_hc_hot_link('anthonyadavisii','HDR','1','test post id')
```

Should output as follows:

```
'https://hivesigner.com/sign/custom_json?authority=active&required_auths=%5B%22anthonyadavisii%22%5D&required_posting_auths=%5B%5D&id=ssc-mainnet-hive&json=%7B%22contractName%22%3A%22tokens%22%2C%22contractAction%22%3A%22transfer%22%2C%22contractPayload%22%3A%7B%22symbol%22%3A%22HDR%22%2C%22to%22%3A%22hive-dr%22%2C%22quantity%22%3A%221%22%2C%22memo%22%3A%22test+post+id%22%7D%7D'
```
![image.png](https://images.ecency.com/DQmSM3gjcQqHZ53kd5W56F9SPxmBo1FVkcEMBHVZ9qEzxMa/image.png)

I plan on refining this so it may be run as a script as well.

### Thank you for your time! You're votes for this work are appreciated!
