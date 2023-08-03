RUN sed -i '1 i echo "!! /etc/bash.nointeractive.bashrc"' /etc/bash.nointeractive.bashrc
RUN sed -i '1 i echo "!! /etc/bash.bashrc - all"' /etc/bash.bashrc
RUN sed -i '10 i echo "!! /etc/bash.bashrc - interactive"' /etc/bash.bashrc
RUN sed -i '1 i echo "!! ~/.bashrc - all"' /etc/skel/.bashrc
RUN sed -i '10 i echo "!! ~/.profile"' /etc/skel/.profile
# Not sure why bashrc works on just the skel and not .profile, and the user
# is created before this by ddev
RUN sed -i '10 i echo "!! ~/.profile"' /home/$username/.profile
RUN sed -i '12 i echo "!! ~/.bashrc - interactive"' /etc/skel/.bashrc
