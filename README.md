# Server Metrics 2026-02-26 08:02:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 32702.0 (9h 5m)
telemt_connections_total 426627
telemt_connections_bad_total 3027
telemt_handshake_timeouts_total 57813
telemt_me_keepalive_sent_total 35697
telemt_me_keepalive_pong_total 35690
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1028
telemt_me_reconnect_success_total 1118
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 80826
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 660
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 392
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 34
telemt_pool_force_close_total 486
telemt_pool_stale_pick_total 12760
telemt_me_writer_removed_total 2011
telemt_me_writer_removed_unexpected_total 1065
telemt_me_refill_triggered_total 1009
telemt_me_refill_skipped_inflight_total 56
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 348081
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 2741159576 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 89291182760 (83.16 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 995.6 (0h 16m)
telemt_connections_total 12051
telemt_handshake_timeouts_total 3810
telemt_me_keepalive_sent_total 986
telemt_me_keepalive_pong_total 986
telemt_me_reconnect_success_total 15
telemt_me_route_drop_no_conn_total 1354
telemt_desync_total 28
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_drain_active 19
telemt_pool_stale_pick_total 244
telemt_me_writer_removed_total 8
telemt_user_connections_total{user="hello"} 7378
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 50440472 (48.10 MB)
telemt_user_octets_to_client{user="hello"} 2496956488 (2.33 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 41223.6 (11h 27m)
telemt_connections_total 282972
telemt_connections_bad_total 1457
telemt_handshake_timeouts_total 75635
telemt_me_keepalive_sent_total 44887
telemt_me_keepalive_pong_total 44871
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 3110
telemt_me_reconnect_success_total 3293
telemt_me_route_drop_no_conn_total 45881
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 510
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 43
telemt_pool_force_close_total 461
telemt_pool_stale_pick_total 6766
telemt_me_writer_removed_total 4408
telemt_me_writer_removed_unexpected_total 3193
telemt_me_refill_triggered_total 3085
telemt_me_refill_skipped_inflight_total 108
telemt_me_writer_restored_same_endpoint_total 3075
telemt_me_writer_restored_fallback_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 194379
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 1519359172 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 52112952268 (48.53 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 43629.5 (12h 7m)
telemt_connections_total 242547
telemt_connections_bad_total 4458
telemt_handshake_timeouts_total 21417
telemt_me_keepalive_sent_total 48299
telemt_me_keepalive_pong_total 48270
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2145
telemt_me_reconnect_success_total 2306
telemt_me_route_drop_no_conn_total 57348
telemt_me_route_drop_channel_closed_total 2
telemt_desync_total 465
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 45
telemt_pool_force_close_total 479
telemt_pool_stale_pick_total 8685
telemt_me_writer_removed_total 3457
telemt_me_writer_removed_unexpected_total 2228
telemt_me_refill_triggered_total 2109
telemt_me_refill_skipped_inflight_total 119
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2098
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 191142
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1166113484 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 36308384572 (33.81 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 43942.0 (12h 12m)
telemt_connections_total 380137
telemt_connections_bad_total 720
telemt_handshake_timeouts_total 64045
telemt_me_keepalive_sent_total 48474
telemt_me_keepalive_pong_total 48444
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 1799
telemt_me_reconnect_success_total 1950
telemt_me_route_drop_no_conn_total 106243
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 667
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 46
telemt_pool_drain_active 16
telemt_pool_force_close_total 679
telemt_pool_stale_pick_total 12351
telemt_me_writer_removed_total 3147
telemt_me_writer_removed_unexpected_total 1888
telemt_me_refill_triggered_total 1766
telemt_me_refill_skipped_inflight_total 122
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_restored_fallback_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 306650
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 4488974568 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 118715769196 (110.56 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 41185.4 (11h 26m)
telemt_connections_total 1759
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 865
telemt_me_keepalive_sent_total 44578
telemt_me_keepalive_pong_total 44530
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 12414
telemt_me_reconnect_success_total 12874
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 55
telemt_pool_swap_total 43
telemt_pool_force_close_total 170
telemt_pool_stale_pick_total 20
telemt_me_writer_removed_total 13872
telemt_me_writer_removed_unexpected_total 12762
telemt_me_refill_triggered_total 12408
telemt_me_refill_skipped_inflight_total 354
telemt_me_writer_restored_same_endpoint_total 12405
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello1"} 726
telemt_user_connections_current{user="hello1"} 25
telemt_user_octets_from_client{user="hello1"} 2366932 (2.26 MB)
telemt_user_octets_to_client{user="hello1"} 137879944 (131.49 MB)
```