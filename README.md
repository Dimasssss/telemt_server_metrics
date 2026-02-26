# Server Metrics 2026-02-26 19:18:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.2

telemt_uptime_seconds 157.0 (0h 2m)
telemt_connections_total 3840
telemt_handshake_timeouts_total 262
telemt_me_keepalive_sent_total 276
telemt_me_keepalive_pong_total 273
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 673
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_user_connections_total{user="hello"} 3391
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 9460116 (9.02 MB)
telemt_user_octets_to_client{user="hello"} 375207984 (357.83 MB)
```

## server2

```
telemt 3.1.2

telemt_uptime_seconds 240.8 (0h 4m)
telemt_connections_total 2392
telemt_handshake_timeouts_total 164
telemt_me_keepalive_sent_total 349
telemt_me_keepalive_pong_total 349
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 22
telemt_me_route_drop_no_conn_total 366
telemt_me_writer_removed_total 2
telemt_me_writer_removed_unexpected_total 2
telemt_me_refill_triggered_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 2165
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 7039204 (6.71 MB)
telemt_user_octets_to_client{user="hello"} 412326040 (393.22 MB)
```

## server3

```
telemt 3.1.2

telemt_uptime_seconds 1014.1 (0h 16m)
telemt_connections_total 10416
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 775
telemt_me_keepalive_sent_total 2855
telemt_me_keepalive_pong_total 2851
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 72
telemt_me_route_drop_no_conn_total 2924
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 1
telemt_pool_drain_active 14
telemt_pool_stale_pick_total 345
telemt_me_writer_removed_total 65
telemt_me_writer_removed_unexpected_total 50
telemt_me_refill_triggered_total 41
telemt_me_refill_skipped_inflight_total 9
telemt_me_writer_restored_same_endpoint_total 41
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 9226
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 53853088 (51.36 MB)
telemt_user_octets_to_client{user="hello"} 4972057304 (4.63 GB)
```

## server4

```
telemt 3.1.2

telemt_uptime_seconds 2185.8 (0h 36m)
telemt_connections_total 18364
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1935
telemt_me_keepalive_sent_total 6233
telemt_me_keepalive_pong_total 6229
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 101
telemt_me_reconnect_success_total 124
telemt_me_route_drop_no_conn_total 5113
telemt_desync_total 47
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 894
telemt_me_writer_removed_total 158
telemt_me_writer_removed_unexpected_total 100
telemt_me_refill_triggered_total 80
telemt_me_refill_skipped_inflight_total 20
telemt_me_writer_restored_same_endpoint_total 80
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 15994
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 105065232 (100.20 MB)
telemt_user_octets_to_client{user="hello"} 3316212140 (3.09 GB)
```

## server5

```
telemt 3.1.2

telemt_uptime_seconds 2542.2 (0h 42m)
telemt_connections_total 48747
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 9805
telemt_me_keepalive_sent_total 4975
telemt_me_keepalive_pong_total 4972
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 88
telemt_me_route_drop_no_conn_total 12346
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 54
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 2
telemt_pool_force_close_total 41
telemt_pool_stale_pick_total 1197
telemt_me_writer_removed_total 122
telemt_me_writer_removed_unexpected_total 66
telemt_me_refill_triggered_total 56
telemt_me_refill_skipped_inflight_total 10
telemt_me_writer_restored_same_endpoint_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 37698
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 330864324 (315.54 MB)
telemt_user_octets_to_client{user="hello"} 17776072472 (16.56 GB)
```

## reserve server

```
telemt 3.1.2

telemt_uptime_seconds 2192.0 (0h 36m)
telemt_connections_total 49
telemt_connections_bad_total 2
telemt_me_keepalive_sent_total 9928
telemt_me_keepalive_pong_total 9915
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 602
telemt_me_reconnect_success_total 649
telemt_pool_swap_total 2
telemt_pool_force_close_total 7
telemt_me_writer_removed_total 676
telemt_me_writer_removed_unexpected_total 620
telemt_me_refill_triggered_total 589
telemt_me_refill_skipped_inflight_total 31
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello1"} 46
telemt_user_connections_current{user="hello1"} 6
telemt_user_octets_from_client{user="hello1"} 90488 (88.37 KB)
telemt_user_octets_to_client{user="hello1"} 3781796 (3.61 MB)
```