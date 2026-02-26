# Server Metrics 2026-02-26 19:12:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 72905.9 (20h 15m)
telemt_connections_total 1542167
telemt_connections_bad_total 7213
telemt_handshake_timeouts_total 262088
telemt_me_keepalive_sent_total 79907
telemt_me_keepalive_pong_total 79836
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2008
telemt_me_reconnect_success_total 2145
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 443341
telemt_me_route_drop_channel_closed_total 6
telemt_desync_total 2551
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1613
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 942
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 77
telemt_pool_drain_active 19
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 43363
telemt_me_writer_removed_total 4169
telemt_me_writer_removed_unexpected_total 2053
telemt_me_refill_triggered_total 1927
telemt_me_refill_skipped_inflight_total 126
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1904
telemt_me_writer_restored_fallback_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1202726
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 10466313204 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 329319806628 (306.70 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 41199.2 (11h 26m)
telemt_connections_total 372479
telemt_connections_bad_total 6774
telemt_handshake_timeouts_total 54653
telemt_me_keepalive_sent_total 45852
telemt_me_keepalive_pong_total 45820
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 1883
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 113686
telemt_desync_total 847
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 42
telemt_pool_force_close_total 649
telemt_pool_stale_pick_total 13166
telemt_me_writer_removed_total 2967
telemt_me_writer_removed_unexpected_total 1844
telemt_me_refill_triggered_total 1759
telemt_me_refill_skipped_inflight_total 85
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 295651
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 5181529268 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 91100618664 (84.84 GB)
```

## server3

```
telemt 3.1.2

telemt_uptime_seconds 705.3 (0h 11m)
telemt_connections_total 8125
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 703
telemt_me_keepalive_sent_total 1861
telemt_me_keepalive_pong_total 1860
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 54
telemt_me_route_drop_no_conn_total 2153
telemt_desync_total 7
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_me_writer_removed_total 33
telemt_me_writer_removed_unexpected_total 33
telemt_me_refill_triggered_total 26
telemt_me_refill_skipped_inflight_total 7
telemt_me_writer_restored_same_endpoint_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 7085
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 43364456 (41.36 MB)
telemt_user_octets_to_client{user="hello"} 3627172812 (3.38 GB)
```

## server4

```
telemt 3.1.2

telemt_uptime_seconds 1877.1 (0h 31m)
telemt_connections_total 16431
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1889
telemt_me_keepalive_sent_total 5264
telemt_me_keepalive_pong_total 5260
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 98
telemt_me_route_drop_no_conn_total 4580
telemt_desync_total 39
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 595
telemt_me_writer_removed_total 105
telemt_me_writer_removed_unexpected_total 75
telemt_me_refill_triggered_total 60
telemt_me_refill_skipped_inflight_total 15
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 14151
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 99711384 (95.09 MB)
telemt_user_octets_to_client{user="hello"} 3042182004 (2.83 GB)
```

## server5

```
telemt 3.1.2

telemt_uptime_seconds 2233.6 (0h 37m)
telemt_connections_total 43478
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 7913
telemt_me_keepalive_sent_total 4474
telemt_me_keepalive_pong_total 4471
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 73
telemt_me_route_drop_no_conn_total 11186
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 46
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_pool_force_close_total 41
telemt_pool_stale_pick_total 1197
telemt_me_writer_removed_total 107
telemt_me_writer_removed_unexpected_total 51
telemt_me_refill_triggered_total 45
telemt_me_refill_skipped_inflight_total 6
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 33974
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 300729320 (286.80 MB)
telemt_user_octets_to_client{user="hello"} 16939215924 (15.78 GB)
```

## reserve server

```
telemt 3.1.2

telemt_uptime_seconds 1883.6 (0h 31m)
telemt_connections_total 43
telemt_connections_bad_total 2
telemt_me_keepalive_sent_total 8232
telemt_me_keepalive_pong_total 8220
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 499
telemt_me_reconnect_success_total 543
telemt_pool_swap_total 1
telemt_pool_force_close_total 4
telemt_me_writer_removed_total 545
telemt_me_writer_removed_unexpected_total 512
telemt_me_refill_triggered_total 486
telemt_me_refill_skipped_inflight_total 26
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello1"} 40
telemt_user_connections_current{user="hello1"} 6
telemt_user_octets_from_client{user="hello1"} 81960 (80.04 KB)
telemt_user_octets_to_client{user="hello1"} 3764336 (3.59 MB)
```