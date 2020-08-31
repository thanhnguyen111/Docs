## API

Base URL : https://system.dinos.click/api/v1/push_data

### 1. Post data

>METHOD: POST

>HEADER : “Authorization: Bearer {access_token}”

>BODY: 

    {	
        "name": "network test",
        "phone": "093xxx9123",
        "affiliate_network": "Zawa",
        "address": "Ha Noi",
        "subid": "xxx",
        "sub_2": "id_conversion_net"
    }

>RESPONSE:
>>1.Status: Error

    {
        "status": "error",
        "data": "Push data False!"
    }
        
>>1.Status: Success

    {
        "status": "success",
        "data": {
            "order_id":52904
        }
    }

#  
