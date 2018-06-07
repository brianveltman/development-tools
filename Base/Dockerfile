FROM alpine:3.7

RUN apk update \
    && apk add bash curl git git-lfs nmap python py2-pip tmux wget zsh \
	docker-bash-completion docker-zsh-completion git-bash-completion git-zsh-completion
	
RUN pip install --user powerline-status

#RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
#COPY .zshrc ~/.zshrc
#RUN source ~/.zshrc