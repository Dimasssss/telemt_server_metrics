# Server Metrics 2026-02-25 23:28:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 1856.2 (0h 30m)
telemt_connections_total 15860
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 417
telemt_me_keepalive_sent_total 1913
telemt_me_keepalive_pong_total 1913
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 102
telemt_me_route_drop_no_conn_total 1766
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 12
telemt_pool_stale_pick_total 321
telemt_me_writer_removed_total 112
telemt_me_writer_removed_unexpected_total 84
telemt_me_refill_triggered_total 73
telemt_me_refill_skipped_inflight_total 11
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 14702
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 56525960 (53.91 MB)
telemt_user_octets_to_client{user="hello"} 3016382640 (2.81 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 2650.5 (0h 44m)
telemt_connections_total 10014
telemt_connections_bad_total 417
telemt_handshake_timeouts_total 372
telemt_me_keepalive_sent_total 2882
telemt_me_keepalive_pong_total 2882
telemt_me_reconnect_attempts_total 114
telemt_me_reconnect_success_total 142
telemt_me_route_drop_no_conn_total 1622
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 367
telemt_me_writer_removed_total 175
telemt_me_writer_removed_unexpected_total 119
telemt_me_refill_triggered_total 109
telemt_me_refill_skipped_inflight_total 10
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8928
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 28716892 (27.39 MB)
telemt_user_octets_to_client{user="hello"} 1654549356 (1.54 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 10378.2 (2h 52m)
telemt_connections_total 66842
telemt_connections_bad_total 1340
telemt_handshake_timeouts_total 15816
telemt_me_keepalive_sent_total 11323
telemt_me_keepalive_pong_total 11318
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 597
telemt_me_reconnect_success_total 654
telemt_me_route_drop_no_conn_total 12531
telemt_desync_total 161
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 10
telemt_pool_force_close_total 116
telemt_pool_stale_pick_total 1734
telemt_me_writer_removed_total 898
telemt_me_writer_removed_unexpected_total 615
telemt_me_refill_triggered_total 586
telemt_me_refill_skipped_inflight_total 29
telemt_me_writer_restored_same_endpoint_total 583
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 47960
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 396622208 (378.25 MB)
telemt_user_octets_to_client{user="hello"} 13363772356 (12.45 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 12783.8 (3h 33m)
telemt_connections_total 81002
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 8262
telemt_me_keepalive_sent_total 14310
telemt_me_keepalive_pong_total 14299
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 798
telemt_me_route_drop_no_conn_total 26406
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 175
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 13
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 3187
telemt_me_writer_removed_total 1113
telemt_me_writer_removed_unexpected_total 756
telemt_me_refill_triggered_total 715
telemt_me_refill_skipped_inflight_total 41
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 712
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 66070
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 270098492 (257.59 MB)
telemt_user_octets_to_client{user="hello"} 8066452532 (7.51 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 13096.3 (3h 38m)
telemt_connections_total 100797
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 9705
telemt_me_keepalive_sent_total 14716
telemt_me_keepalive_pong_total 14706
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 639
telemt_me_reconnect_success_total 693
telemt_me_route_drop_no_conn_total 36124
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 192
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 13
telemt_pool_force_close_total 224
telemt_pool_stale_pick_total 3562
telemt_me_writer_removed_total 1017
telemt_me_writer_removed_unexpected_total 660
telemt_me_refill_triggered_total 622
telemt_me_refill_skipped_inflight_total 38
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 89586
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2346140228 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 32412526572 (30.19 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 10339.9 (2h 52m)
telemt_connections_total 122
telemt_connections_bad_total 26
telemt_me_keepalive_sent_total 11117
telemt_me_keepalive_pong_total 11105
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 3220
telemt_me_reconnect_success_total 3354
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 10
telemt_pool_force_close_total 31
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 3563
telemt_me_writer_removed_unexpected_total 3311
telemt_me_refill_triggered_total 3218
telemt_me_refill_skipped_inflight_total 93
telemt_me_writer_restored_same_endpoint_total 3217
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello1"} 96
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 332600 (324.80 KB)
telemt_user_octets_to_client{user="hello1"} 1451304 (1.38 MB)
```