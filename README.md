# Server Metrics 2026-03-04 07:52:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 38484.9 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430258
telemt_connections_bad_total 7923
telemt_handshake_timeouts_total 6129
telemt_upstream_connect_attempt_total 24037
telemt_upstream_connect_success_total 23925
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23925
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 4778
telemt_me_reconnect_success_total 4746
telemt_me_reader_eof_total 4856
telemt_me_idle_close_by_peer_total 4856
telemt_me_route_drop_no_conn_total 140664
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 815
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4856
telemt_me_writer_restored_same_endpoint_total 4725
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 359176
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 4236924716 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 107279305788 (99.91 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 38481.4 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180945
telemt_connections_bad_total 1600
telemt_handshake_timeouts_total 23534
telemt_upstream_connect_attempt_total 78407
telemt_upstream_connect_success_total 77267
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 77261
telemt_upstream_connect_attempts_per_request{bucket="2"} 538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_keepalive_timeout_total 1204
telemt_me_reconnect_attempts_total 45520
telemt_me_reconnect_success_total 45442
telemt_me_reader_eof_total 46554
telemt_me_idle_close_by_peer_total 46553
telemt_me_route_drop_no_conn_total 71173
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 364
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 46634
telemt_me_writer_restored_same_endpoint_total 45417
telemt_me_writer_removed_unexpected_minus_restored_total 1217
telemt_user_connections_total{user="hello"} 128716
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 1349543744 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 50877303064 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 38480.4 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359959
telemt_connections_bad_total 108343
telemt_handshake_timeouts_total 10750
telemt_upstream_connect_attempt_total 58644
telemt_upstream_connect_success_total 58301
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 58300
telemt_upstream_connect_attempts_per_request{bucket="2"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 770
telemt_me_reconnect_attempts_total 26961
telemt_me_reconnect_success_total 26892
telemt_me_reader_eof_total 28359
telemt_me_idle_close_by_peer_total 28356
telemt_me_route_drop_no_conn_total 110536
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 546
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 28370
telemt_me_writer_restored_same_endpoint_total 26871
telemt_me_writer_removed_unexpected_minus_restored_total 1499
telemt_user_connections_total{user="hello"} 230103
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 2160109456 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 82859237212 (77.17 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 38479.2 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205566
telemt_connections_bad_total 16734
telemt_handshake_timeouts_total 7791
telemt_upstream_connect_attempt_total 29246
telemt_upstream_connect_success_total 29125
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 29125
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 331
telemt_me_reconnect_attempts_total 6249
telemt_me_reconnect_success_total 6235
telemt_me_reader_eof_total 6354
telemt_me_idle_close_by_peer_total 6354
telemt_me_route_drop_no_conn_total 66872
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6354
telemt_me_writer_restored_same_endpoint_total 6214
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 162170
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 1699229600 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 58078879620 (54.09 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 38477.9 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351357
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 130470
telemt_upstream_connect_attempt_total 55307
telemt_upstream_connect_success_total 54918
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 54918
telemt_upstream_connect_attempts_per_request{bucket="2"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 758
telemt_me_reconnect_attempts_total 25726
telemt_me_reconnect_success_total 25706
telemt_me_reader_eof_total 27067
telemt_me_idle_close_by_peer_total 27066
telemt_me_route_drop_no_conn_total 98334
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 235
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 27081
telemt_me_writer_restored_same_endpoint_total 25681
telemt_me_writer_removed_unexpected_minus_restored_total 1400
telemt_user_connections_total{user="hello"} 207608
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 2667576712 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 51038620468 (47.53 GB)
telemt_user_unique_ips_current{user="hello"} 46
```