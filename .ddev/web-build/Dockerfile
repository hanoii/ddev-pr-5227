RUN sed -i '1 i echo "!! /etc/bash.nointeractive.bashrc"' /etc/bash.nointeractive.bashrc
RUN sed -i '1 i echo "!! /etc/bash.bashrc - all"' /etc/bash.bashrc
RUN sed -i '10 i echo "!! /etc/bash.bashrc - interactive"' /etc/bash.bashrc
RUN sed -i '10 i echo "!! ~/.profile"' /home/$username/.profile
RUN sed -i '1 i echo "!! ~/.bashrc - all"' /home/$username/.bashrc
RUN sed -i '12 i echo "!! ~/.bashrc - interactive"' /home/$username/.bashrc
