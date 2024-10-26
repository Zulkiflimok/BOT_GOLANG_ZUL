



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
