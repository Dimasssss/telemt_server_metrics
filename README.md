# Server Metrics 2026-03-04 07:00:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 35410.9 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354442
telemt_connections_bad_total 6000
telemt_handshake_timeouts_total 5857
telemt_upstream_connect_attempt_total 22865
telemt_upstream_connect_success_total 22756
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 22756
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4659
telemt_me_reconnect_success_total 4634
telemt_me_reader_eof_total 4743
telemt_me_idle_close_by_peer_total 4743
telemt_me_route_drop_no_conn_total 120402
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 747
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4743
telemt_me_writer_restored_same_endpoint_total 4614
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 303458
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 3269406408 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 93736760932 (87.30 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 35407.5 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158507
telemt_connections_bad_total 1229
telemt_handshake_timeouts_total 22724
telemt_upstream_connect_attempt_total 73509
telemt_upstream_connect_success_total 72459
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 72453
telemt_upstream_connect_attempts_per_request{bucket="2"} 492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 1158
telemt_me_reconnect_attempts_total 43241
telemt_me_reconnect_success_total 43167
telemt_me_reader_eof_total 44241
telemt_me_idle_close_by_peer_total 44240
telemt_me_route_drop_no_conn_total 55035
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 295
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44321
telemt_me_writer_restored_same_endpoint_total 43142
telemt_me_writer_removed_unexpected_minus_restored_total 1179
telemt_user_connections_total{user="hello"} 108079
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1041406352 (993.16 MB)
telemt_user_octets_to_client{user="hello"} 43833122020 (40.82 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 35406.3 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312177
telemt_connections_bad_total 100434
telemt_handshake_timeouts_total 8975
telemt_upstream_connect_attempt_total 50847
telemt_upstream_connect_success_total 50531
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 50530
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 665
telemt_me_reconnect_attempts_total 22073
telemt_me_reconnect_success_total 22016
telemt_me_reader_eof_total 23230
telemt_me_idle_close_by_peer_total 23227
telemt_me_route_drop_no_conn_total 82263
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 482
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 23239
telemt_me_writer_restored_same_endpoint_total 21995
telemt_me_writer_removed_unexpected_minus_restored_total 1244
telemt_user_connections_total{user="hello"} 193988
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 1717404592 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 64644805320 (60.21 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 35405.2 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176784
telemt_connections_bad_total 13972
telemt_handshake_timeouts_total 6060
telemt_upstream_connect_attempt_total 27196
telemt_upstream_connect_success_total 27081
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 27081
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 5988
telemt_me_reconnect_success_total 5976
telemt_me_reader_eof_total 6092
telemt_me_idle_close_by_peer_total 6092
telemt_me_route_drop_no_conn_total 49880
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6092
telemt_me_writer_restored_same_endpoint_total 5955
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 138714
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 1385619320 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 50876889764 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 35403.8 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317688
telemt_connections_bad_total 6415
telemt_handshake_timeouts_total 128647
telemt_upstream_connect_attempt_total 49324
telemt_upstream_connect_success_total 48986
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 48986
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 663
telemt_me_reconnect_attempts_total 22656
telemt_me_reconnect_success_total 22641
telemt_me_reader_eof_total 23856
telemt_me_idle_close_by_peer_total 23855
telemt_me_route_drop_no_conn_total 82191
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 226
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23869
telemt_me_writer_restored_same_endpoint_total 22616
telemt_me_writer_removed_unexpected_minus_restored_total 1253
telemt_user_connections_total{user="hello"} 176760
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 2360925160 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 39894004672 (37.15 GB)
telemt_user_unique_ips_current{user="hello"} 34
```