# Server Metrics 2026-03-06 23:23:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 18897.3 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275930
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 9262
telemt_upstream_connect_attempt_total 41184
telemt_upstream_connect_success_total 40368
telemt_upstream_connect_fail_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 41047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 679
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 18559
telemt_me_reconnect_success_total 17923
telemt_me_reader_eof_total 20614
telemt_me_idle_close_by_peer_total 20614
telemt_me_route_drop_no_conn_total 108993
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 863
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 614
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 6
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 20724
telemt_me_writer_restored_same_endpoint_total 17880
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 11301
telemt_me_writer_removed_unexpected_minus_restored_total 2807
telemt_user_connections_total{user="hello"} 249493
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 3969100112 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 113662215544 (105.86 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 18897.3 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114361
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 11376
telemt_upstream_connect_attempt_total 64189
telemt_upstream_connect_success_total 64187
telemt_upstream_connect_attempts_per_request{bucket="1"} 64187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 800
telemt_me_reconnect_attempts_total 38658
telemt_me_reconnect_success_total 38506
telemt_me_reader_eof_total 38908
telemt_me_idle_close_by_peer_total 38904
telemt_me_route_drop_no_conn_total 39502
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 706
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 10
telemt_pool_force_close_total 519
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 38931
telemt_me_writer_restored_same_endpoint_total 38504
telemt_me_async_recovery_trigger_total 11293
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 97082
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 1469509496 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 35548823908 (33.11 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 18897.3 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212909
telemt_connections_bad_total 917
telemt_handshake_timeouts_total 3511
telemt_upstream_connect_attempt_total 49158
telemt_upstream_connect_success_total 48999
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 49049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1480
telemt_me_reconnect_attempts_total 27212
telemt_me_reconnect_success_total 27166
telemt_me_reader_eof_total 28741
telemt_me_idle_close_by_peer_total 28738
telemt_me_route_drop_no_conn_total 81290
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 966
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 723
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 10
telemt_pool_force_close_total 299
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 28895
telemt_me_writer_restored_same_endpoint_total 27159
telemt_me_async_recovery_trigger_total 33738
telemt_me_writer_removed_unexpected_minus_restored_total 1736
telemt_user_connections_total{user="hello"} 197911
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 15127995956 (14.09 GB)
telemt_user_octets_to_client{user="hello"} 58731319324 (54.70 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 18897.6 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212635
telemt_connections_bad_total 56956
telemt_handshake_timeouts_total 16166
telemt_upstream_connect_attempt_total 32062
telemt_upstream_connect_success_total 31984
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 638
telemt_me_reconnect_attempts_total 10093
telemt_me_reconnect_success_total 10073
telemt_me_reader_eof_total 13526
telemt_me_idle_close_by_peer_total 13525
telemt_me_route_drop_no_conn_total 56562
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_pool_force_close_total 368
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 13532
telemt_me_writer_restored_same_endpoint_total 10068
telemt_me_writer_removed_unexpected_minus_restored_total 3464
telemt_user_connections_total{user="hello"} 135917
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1653128380 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 43063039120 (40.11 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 18896.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184956
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 1713
telemt_upstream_connect_attempt_total 29572
telemt_upstream_connect_success_total 29433
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 29452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 933
telemt_me_reconnect_attempts_total 8672
telemt_me_reconnect_success_total 8642
telemt_me_reader_eof_total 11682
telemt_me_idle_close_by_peer_total 11681
telemt_me_route_drop_no_conn_total 62956
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 752
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 10
telemt_pool_force_close_total 351
telemt_pool_stale_pick_total 212
telemt_me_writer_removed_unexpected_total 11749
telemt_me_writer_restored_same_endpoint_total 8638
telemt_me_writer_removed_unexpected_minus_restored_total 3111
telemt_user_connections_total{user="hello"} 169339
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 10050703772 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 58990745780 (54.94 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```