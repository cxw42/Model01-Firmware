#!/bin/bash
# Clear Model01 (1024-byte) EEPROM to 0

read -p "Are you sure? " yn

if [[ "$1" != y ]]; then
  echo Aborting
  exit 0
fi

./focus eeprom.contents `perl -E 'print "0 " x 1024'`
