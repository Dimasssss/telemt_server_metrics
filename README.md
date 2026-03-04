# Server Metrics 2026-03-04 11:11:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 50480.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794280
telemt_connections_bad_total 11432
telemt_handshake_timeouts_total 10297
telemt_upstream_connect_attempt_total 31950
telemt_upstream_connect_success_total 31815
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31815
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 7078
telemt_me_reconnect_success_total 7032
telemt_me_reader_eof_total 7251
telemt_me_idle_close_by_peer_total 7251
telemt_me_route_drop_no_conn_total 309008
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1308
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 12
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7251
telemt_me_writer_restored_same_endpoint_total 7011
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 645515
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 7114192664 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 194687123184 (181.32 GB)
telemt_user_unique_ips_current{user="hello"} 113
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 50476.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311602
telemt_connections_bad_total 2815
telemt_handshake_timeouts_total 27174
telemt_upstream_connect_attempt_total 97390
telemt_upstream_connect_success_total 95938
telemt_upstream_connect_fail_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 95932
telemt_upstream_connect_attempts_per_request{bucket="2"} 694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 688
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 55258
telemt_me_reconnect_success_total 55172
telemt_me_reader_eof_total 56582
telemt_me_idle_close_by_peer_total 56581
telemt_me_route_drop_no_conn_total 136833
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 584
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 56662
telemt_me_writer_restored_same_endpoint_total 55147
telemt_me_writer_removed_unexpected_minus_restored_total 1515
telemt_user_connections_total{user="hello"} 240868
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 2901387552 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 78585804132 (73.19 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 50475.7 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612208
telemt_connections_bad_total 152113
telemt_handshake_timeouts_total 18615
telemt_upstream_connect_attempt_total 76026
telemt_upstream_connect_success_total 75585
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 75584
telemt_upstream_connect_attempts_per_request{bucket="2"} 212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 35645
telemt_me_reconnect_success_total 35556
telemt_me_reader_eof_total 37482
telemt_me_idle_close_by_peer_total 37478
telemt_me_route_drop_no_conn_total 227967
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1066
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 37494
telemt_me_writer_restored_same_endpoint_total 35535
telemt_me_writer_removed_unexpected_minus_restored_total 1959
telemt_user_connections_total{user="hello"} 422538
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 5316328456 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 142570337820 (132.78 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 50474.7 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398760
telemt_connections_bad_total 27535
telemt_handshake_timeouts_total 66259
telemt_upstream_connect_attempt_total 37850
telemt_upstream_connect_success_total 37701
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 37701
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 421
telemt_me_reconnect_attempts_total 8157
telemt_me_reconnect_success_total 8130
telemt_me_reader_eof_total 8309
telemt_me_idle_close_by_peer_total 8309
telemt_me_route_drop_no_conn_total 112711
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 224
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 13
telemt_pool_force_close_total 317
telemt_me_writer_removed_unexpected_total 8309
telemt_me_writer_restored_same_endpoint_total 8109
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 282929
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 3385063796 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 102951565208 (95.88 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 50473.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537966
telemt_connections_bad_total 6813
telemt_handshake_timeouts_total 132401
telemt_upstream_connect_attempt_total 71774
telemt_upstream_connect_success_total 71288
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 71288
telemt_upstream_connect_attempts_per_request{bucket="2"} 230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 934
telemt_me_reconnect_attempts_total 34627
telemt_me_reconnect_success_total 34594
telemt_me_reader_eof_total 36296
telemt_me_idle_close_by_peer_total 36295
telemt_me_route_drop_no_conn_total 169625
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 677
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 36308
telemt_me_writer_restored_same_endpoint_total 34569
telemt_me_writer_removed_unexpected_minus_restored_total 1739
telemt_user_connections_total{user="hello"} 374469
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 4888165196 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 100234298040 (93.35 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 55
```