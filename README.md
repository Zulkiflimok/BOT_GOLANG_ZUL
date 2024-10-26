#TEAM TERMUX ZULKIFLI MOKOAGOW

# Creator bots 1
<a href="https://line.me/R/ti/p/~zul.1.02"><img height="36" border="0" alt="PrankBots" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>
# Creator bots 2
<a href="https://line.me/R/ti/p/~kuis.1.1"><img height="36" border="0" alt="Add Friend" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>
# Creator bots 3
<a href="https://line.me/R/ti/p/~@936qdoju"><img height="36" border="0" alt="Add Friend" src="https://scdn.line-apps.com/n/line_add_friends/btn/en.png"></a>




# cara jalanin bot golang

apt install git -y
echo "export GOPATH=workspace/go" >> ~/.bash_profile && export GOPATH=workspace/go/src && export GOROOT=/usr/local/go && export GOPATH=$HOME/Projects && export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
go env -w GO111MODULE=off
go get github.com/dchest/siphash
go get github.com/panjf2000/ants
go get github.com/shirou/gopsutil/mem
go get github.com/tidwall/gjson
go get golang.org/x/net/http2
go get github.com/kardianos/osext
go get github.com/asaskevich/govalidator
go get github.com/shirou/gopsutil/host
go get github.com/valyala/fasthttp
go get github.com/cheggaaa/pb/v3
go get github.com/Dhome12/imroc/req
rm -r go1.19.5.linux-amd64.tar.gz.1
export GOPATH=$HOME
export GOROOT=/usr/local/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH


go env -w GO111MODULE=off && go get github.com/dchest/siphash &&go get github.com/panjf2000/ants && go get github.com/shirou/gopsutil/mem && go get github.com/tidwall/gjson && go get golang.org/x/net/http2 && go get github.com/kardianos/osext


cd zulkifli

echo "export GOPATH=workspace/go" >> ~/.bash_profile && export GOPATH=workspace/go/src && export GOROOT=/usr/local/go && export GOPATH=$HOME/Projects && export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

screen

python3 zul.py
