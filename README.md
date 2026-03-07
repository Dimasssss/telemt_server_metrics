# Server Metrics 2026-03-07 02:33:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 30298.3 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335051
telemt_connections_bad_total 3896
telemt_handshake_timeouts_total 9640
telemt_upstream_connect_attempt_total 102014
telemt_upstream_connect_success_total 98935
telemt_upstream_connect_fail_total 2924
telemt_upstream_connect_attempts_per_request{bucket="1"} 101859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2924
telemt_me_keepalive_timeout_total 2069
telemt_me_reconnect_attempts_total 64043
telemt_me_reconnect_success_total 61214
telemt_me_reader_eof_total 64088
telemt_me_idle_close_by_peer_total 64085
telemt_me_route_drop_no_conn_total 125280
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1177
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 519
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 14
telemt_pool_force_close_total 628
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 64202
telemt_me_writer_restored_same_endpoint_total 61036
telemt_me_writer_restored_fallback_total 172
telemt_me_async_recovery_trigger_total 56646
telemt_me_writer_removed_unexpected_minus_restored_total 2994
telemt_user_connections_total{user="hello"} 305217
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 4471875932 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 133183904244 (124.04 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 30298.3 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147262
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 20294
telemt_upstream_connect_attempt_total 213012
telemt_upstream_connect_success_total 213009
telemt_upstream_connect_attempts_per_request{bucket="1"} 213009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1593
telemt_me_reconnect_attempts_total 168898
telemt_me_reconnect_success_total 168419
telemt_me_reader_eof_total 151934
telemt_me_idle_close_by_peer_total 151929
telemt_me_route_drop_no_conn_total 44893
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 847
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 23
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 151975
telemt_me_writer_restored_same_endpoint_total 168417
telemt_me_async_recovery_trigger_total 56640
telemt_user_connections_total{user="hello"} 119669
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1624122324 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 40423221608 (37.65 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 30298.3 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260964
telemt_connections_bad_total 1473
telemt_handshake_timeouts_total 4395
telemt_upstream_connect_attempt_total 162833
telemt_upstream_connect_success_total 162596
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 162686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 2843
telemt_me_reconnect_attempts_total 124336
telemt_me_reconnect_success_total 124239
telemt_me_reader_eof_total 126491
telemt_me_idle_close_by_peer_total 126486
telemt_me_route_drop_no_conn_total 95377
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 251
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1104
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 16
telemt_pool_force_close_total 406
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 126682
telemt_me_writer_restored_same_endpoint_total 124232
telemt_me_async_recovery_trigger_total 169652
telemt_me_writer_removed_unexpected_minus_restored_total 2450
telemt_user_connections_total{user="hello"} 244002
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 24308271324 (22.64 GB)
telemt_user_octets_to_client{user="hello"} 68369985104 (63.67 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 30298.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270896
telemt_connections_bad_total 83748
telemt_handshake_timeouts_total 17676
telemt_upstream_connect_attempt_total 60530
telemt_upstream_connect_success_total 60439
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 60483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1146
telemt_me_reconnect_attempts_total 21840
telemt_me_reconnect_success_total 21805
telemt_me_reader_eof_total 29701
telemt_me_idle_close_by_peer_total 29699
telemt_me_route_drop_no_conn_total 74007
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 258
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 29706
telemt_me_writer_restored_same_endpoint_total 21800
telemt_me_writer_removed_unexpected_minus_restored_total 7906
telemt_user_connections_total{user="hello"} 165201
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1822669980 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 52451479740 (48.85 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 30296.9 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228199
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 2969
telemt_upstream_connect_attempt_total 51094
telemt_upstream_connect_success_total 50899
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 50923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1355
telemt_me_reconnect_attempts_total 14828
telemt_me_reconnect_success_total 14786
telemt_me_reader_eof_total 20380
telemt_me_idle_close_by_peer_total 20378
telemt_me_route_drop_no_conn_total 74586
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 814
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 19
telemt_pool_force_close_total 508
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 20449
telemt_me_writer_restored_same_endpoint_total 14778
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5667
telemt_user_connections_total{user="hello"} 209589
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 10338688972 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 80227216840 (74.72 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```