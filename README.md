# Actual Auth Header example

A test project used to confirm  https://github.com/actualbudget/actual PRs related to header auth.

The proposed feature is to allow the actual server's `/account/login` accept a `X-ACTUAL-PASSWORD` header with the password and return the logged in token.

## Details

This includes a docker compose file with an nginx config intended to be used as a proxy in front of your actual server. This is meant for testing purposes, as once setup, this proxy will always automatically log you in to actual if you are accessing the website through this proxy.

## Usage

Copy the `.env.example` file to `.env` and update the env variables to match your setup.

