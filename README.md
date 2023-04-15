## installation guide
```shell
npm install --save-dev hardhat
npx hardhat
npm install @openzeppelin/contracts
```

## how to use hardhat
- https://dashboard.alchemy.com/
```shell
export ALCHEMY_API_KEY=
export MUMBAI_PRIVATE_KEY=
export METADATA_URL=
npx hardhat run scripts/deploy.ts --network mumbai
```

- `env` 명령어를 통해 위에 `export` 명령어로 등록한 환경변수를 shell에서 확인할 수 있다


