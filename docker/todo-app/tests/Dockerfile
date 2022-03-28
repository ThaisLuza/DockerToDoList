FROM mjgargani/docker:dind-trybe1.0
WORKDIR /
EXPOSE 3000
ADD node_modules.tar.gz ./
COPY . ./
CMD [ "npm", "test" ]
