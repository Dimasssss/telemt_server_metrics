# Server Metrics 2026-03-04 09:08:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 43099.3 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551000
telemt_connections_bad_total 10408
telemt_handshake_timeouts_total 6740
telemt_upstream_connect_attempt_total 27248
telemt_upstream_connect_success_total 27131
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 27131
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 5633
telemt_me_reconnect_success_total 5594
telemt_me_reader_eof_total 5745
telemt_me_idle_close_by_peer_total 5745
telemt_me_route_drop_no_conn_total 190680
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 964
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5745
telemt_me_writer_restored_same_endpoint_total 5573
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 459233
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 5294901496 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 136405531152 (127.04 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 43095.8 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221614
telemt_connections_bad_total 1972
telemt_handshake_timeouts_total 24355
telemt_upstream_connect_attempt_total 89095
telemt_upstream_connect_success_total 87827
telemt_upstream_connect_fail_total 596
telemt_upstream_connect_attempts_per_request{bucket="1"} 87821
telemt_upstream_connect_attempts_per_request{bucket="2"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 596
telemt_me_keepalive_timeout_total 1277
telemt_me_reconnect_attempts_total 51734
telemt_me_reconnect_success_total 51654
telemt_me_reader_eof_total 52976
telemt_me_idle_close_by_peer_total 52975
telemt_me_route_drop_no_conn_total 102883
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 496
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 53056
telemt_me_writer_restored_same_endpoint_total 51629
telemt_me_writer_removed_unexpected_minus_restored_total 1427
telemt_user_connections_total{user="hello"} 167034
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 1975525640 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 59498132368 (55.41 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 43094.7 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458583
telemt_connections_bad_total 128497
telemt_handshake_timeouts_total 13420
telemt_upstream_connect_attempt_total 62370
telemt_upstream_connect_success_total 61978
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 61977
telemt_upstream_connect_attempts_per_request{bucket="2"} 188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 833
telemt_me_reconnect_attempts_total 28225
telemt_me_reconnect_success_total 28150
telemt_me_reader_eof_total 29709
telemt_me_idle_close_by_peer_total 29706
telemt_me_route_drop_no_conn_total 153695
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 700
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 29720
telemt_me_writer_restored_same_endpoint_total 28129
telemt_me_writer_removed_unexpected_minus_restored_total 1591
telemt_user_connections_total{user="hello"} 301031
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 2921366900 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 112123075588 (104.42 GB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 43093.7 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285533
telemt_connections_bad_total 20877
telemt_handshake_timeouts_total 36589
telemt_upstream_connect_attempt_total 31772
telemt_upstream_connect_success_total 31643
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31643
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 6538
telemt_me_reconnect_success_total 6517
telemt_me_reader_eof_total 6642
telemt_me_idle_close_by_peer_total 6642
telemt_me_route_drop_no_conn_total 84100
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6642
telemt_me_writer_restored_same_endpoint_total 6496
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 207453
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 2302926052 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 72846684752 (67.84 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 43092.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421786
telemt_connections_bad_total 6454
telemt_handshake_timeouts_total 132070
telemt_upstream_connect_attempt_total 67169
telemt_upstream_connect_success_total 66750
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 66750
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 33217
telemt_me_reconnect_success_total 33190
telemt_me_reader_eof_total 34852
telemt_me_idle_close_by_peer_total 34851
telemt_me_route_drop_no_conn_total 126731
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 316
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 4
telemt_pool_force_close_total 118
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 34864
telemt_me_writer_restored_same_endpoint_total 33165
telemt_me_writer_removed_unexpected_minus_restored_total 1699
telemt_user_connections_total{user="hello"} 267672
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 3864982688 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 67045515296 (62.44 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 60
```