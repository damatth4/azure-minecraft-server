# syntax=docker/dockerfile:1
FROM ubuntu
WORKDIR /app
COPY . .
RUN wget -o /mnt/c/Users/dmatthews/Downloads/Geyser-Spigot.jar https://ci.opencollab.dev/job/GeyserMC/job/Geyser/job/master/lastSuccessfulBuild/artifact/bootstrap/spigot/build/libs/Geyser-Spigot.jar
CMD ["node", "src/index.js"]
EXPOSE 3000