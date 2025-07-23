#TEAM TERMUX ZULKIFLI MOKOAGOW

# Creator bots 1
<a href="https://line.me/R/ti/p/~zul.1.02"><img height="36" border="0" alt="PrankBots" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>
# Creator bots 2
<a href="https://line.me/ti/p/KWbhkYx8y6"><img height="36" border="0" alt="Add Friend" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>
# Creator bots 3
<a href="https://line.me/R/ti/p/~@936qdoju"><img height="36" border="0" alt="Add Friend" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>




# cara jalanin bot golang

Jangan apt install golang-go

1. wget https://go.dev/dl/go1.21.4.linux-amd64.tar.gz
2. rm -rf /usr/local/go && tar -C /usr/local -xzf go1.21.4.linux-amd64.tar.gz
3. nano /etc/profile
Tempel Di Nano dibawa fi : export PATH=$PATH:/usr/local/go/bin
ctrl + x + y
4. source /etc/profile
5. go version


jika Go Version Sudah [ 1.19.4 ] Install Modul Dibawah Ini

#============================================

export GOPATH=$HOME
export GOROOT=/usr/local/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

echo "export GOPATH=workspace/go" >> ~/.bash_profile && export GOPATH=workspace/go/src && export GOROOT=/usr/local/go && export GOPATH=$HOME/Projects && export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
go env -w GO111MODULE=off
go get github.com/dchest/siphash
go get github.com/shirou/gopsutil/mem
go get golang.org/x/net/http2
go get github.com/kardianos/osext
go get github.com/cheggaaa/pb/v3
go get github.com/shirou/gopsutil/mem
go get github.com/kardianos/osext
go get github.com/tidwall/gjson
go get github.com/tidwall/sjson
go get github.com/panjf2000/ants
go get github.com/asaskevich/govalidator
go get github.com/sashabaranov/go-openai
go get github.com/apache/thrift/lib/go/thrift
go get github.com/danielgtaylor/unistyle
go get github.com/lynn9388/supsub
go get github.com/valyala/fasthttp
go get golang.org/x/crypto/curve25519
go get github.com/OneOfOne/xxhash
go get github.com/bashery/botline/thriftjos
go get github.com/skip2/go-qrcode
go get github.com/opalmer/check-go-version/api

curl -sSL https://go.dev/dl/ | grep -o 'go[0-9]\+\.[0-9]\+\.[0-9]\+\.linux-amd64.tar.gz' | head -1 | sed 's/go//' | sed 's/\.linux-amd64.tar.gz//' | xargs -I {} sh -c 'wget https://go.dev/dl/go{}.linux-amd64.tar.gz && sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf go{}.linux-amd64.tar.gz && rm go{}.linux-amd64.tar.gz && echo "Go {} installed successfully"'

cd zulkifli

echo "export GOPATH=workspace/go" >> ~/.bash_profile && export GOPATH=workspace/go/src && export GOROOT=/usr/local/go && export GOPATH=$HOME/Projects && export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

screen

python3 zul.py
