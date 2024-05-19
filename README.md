# packet_buddy
**pcap analysis provided by chatGPT 4 Turbo**

Some fix and enhancements based on [https://github.com/automateyournetwork/packet_buddy](https://github.com/automateyournetwork/packet_buddy)

(The author, John Capobianco, is now focused on ollama, as we want to stay on openai chatgpt)

## Getting started

Clone the repo

Modify the docker-compose.yaml :
```console
OPENAI_API_KEY=<your openapi project api secret key>
```

## Build and Bring up the server
```docker-compose build```

```docker-compose up```

## Visit localhost
http://localhost:8505

### Usage
This has been tested with a variety of small .pcap files and works best with smaller data sets. 

If possible use wireshark filters or other methods to limit the size of the .pcap and number of packets you wish to 'chat' with.
