FROM public.ecr.aws/acentrik/oceanprotocol/algo_dockers:python-full

ENV AWS_WEB_IDENTITY_TOKEN_FILE=
ENV AWS_ROLE_ARN=
ENV GPG_KEY=
ENV secret=


RUN useradd -u 8877 john
RUN chmod 777 /
USER john