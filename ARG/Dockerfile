ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120hrs"
ENV duration=$duration    
RUN echo "Course: $course, Duration: $duration"
CMD ["sleep" , "222"]