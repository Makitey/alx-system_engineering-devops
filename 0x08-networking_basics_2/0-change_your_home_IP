#!/usr/bin/env bash
# Change localhost address
cp /etc/hosts ~/hosts.new
sed -i "s/^127[0-9.]*\slocalhost/127.0.0.2 localhost/" ~/hosts.new
sed -i "$ a\8.8.8.8 facebook.com" ~/hosts.new
cp -f ~/hosts.new /etc/hosts
