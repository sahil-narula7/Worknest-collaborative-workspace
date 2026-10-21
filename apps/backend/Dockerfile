FROM oven/bun:1.3.11

WORKDIR /app
COPY package.json ./
RUN bun install --production
COPY . .

EXPOSE 10000
CMD ["bun", "index.ts"]