# Server Metrics 2026-03-04 16:55:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 71081.1 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1378292
telemt_connections_bad_total 19546
telemt_handshake_timeouts_total 23219
telemt_upstream_connect_attempt_total 41770
telemt_upstream_connect_success_total 41583
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 41583
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 9216
telemt_me_reconnect_success_total 9146
telemt_me_reader_eof_total 9469
telemt_me_idle_close_by_peer_total 9468
telemt_me_route_drop_no_conn_total 546286
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3017
telemt_desync_full_logged_total 953
telemt_desync_suppressed_total 2064
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1035
telemt_pool_swap_total 18
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 235
telemt_me_writer_removed_unexpected_total 9470
telemt_me_writer_restored_same_endpoint_total 9124
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 1127116
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 15079661064 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 377326099268 (351.41 GB)
telemt_user_unique_ips_current{user="hello"} 102
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 71077.6 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529554
telemt_connections_bad_total 6803
telemt_handshake_timeouts_total 30846
telemt_upstream_connect_attempt_total 125260
telemt_upstream_connect_success_total 123426
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 123420
telemt_upstream_connect_attempts_per_request{bucket="2"} 885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_timeout_total 1645
telemt_me_reconnect_attempts_total 67836
telemt_me_reconnect_success_total 67729
telemt_me_reader_eof_total 69468
telemt_me_idle_close_by_peer_total 69467
telemt_me_route_drop_no_conn_total 224037
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1337
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 69548
telemt_me_writer_restored_same_endpoint_total 67703
telemt_me_writer_removed_unexpected_minus_restored_total 1845
telemt_user_connections_total{user="hello"} 425192
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 6271201916 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 133395349648 (124.23 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 71076.4 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060133
telemt_connections_bad_total 210402
telemt_handshake_timeouts_total 30484
telemt_upstream_connect_attempt_total 91452
telemt_upstream_connect_success_total 90812
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 90811
telemt_upstream_connect_attempts_per_request{bucket="2"} 311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 40382
telemt_me_reconnect_success_total 40273
telemt_me_reader_eof_total 42398
telemt_me_idle_close_by_peer_total 42393
telemt_me_route_drop_no_conn_total 392683
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2220
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42411
telemt_me_writer_restored_same_endpoint_total 40251
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 769279
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 14754415768 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 266041308732 (247.77 GB)
telemt_user_unique_ips_current{user="hello"} 79
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 17753.7 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289578
telemt_connections_bad_total 35307
telemt_handshake_timeouts_total 6645
telemt_upstream_connect_attempt_total 7021
telemt_upstream_connect_success_total 7021
telemt_upstream_connect_attempts_per_request{bucket="1"} 7021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3101
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 916
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 933
telemt_me_idle_close_by_peer_total 933
telemt_me_route_drop_no_conn_total 100037
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 316
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_restored_same_endpoint_total 901
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 237742
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 2964991228 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 87809205880 (81.78 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 18113.2 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307911
telemt_connections_bad_total 3079
telemt_handshake_timeouts_total 4197
telemt_upstream_connect_attempt_total 8880
telemt_upstream_connect_success_total 8834
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8834
telemt_upstream_connect_attempts_per_request{bucket="2"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 1442
telemt_me_reconnect_success_total 1445
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 126222
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 566
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_restored_same_endpoint_total 1424
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 267642
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 4398264284 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 79885372508 (74.40 GB)
telemt_user_unique_ips_current{user="hello"} 54
```