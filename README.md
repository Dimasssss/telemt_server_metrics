# Server Metrics 2026-03-11 14:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86026.7 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2068410
telemt_connections_bad_total 30207
telemt_handshake_timeouts_total 52037
telemt_upstream_connect_attempt_total 18153
telemt_upstream_connect_success_total 18142
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 18153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 4650
telemt_me_reconnect_attempts_total 27651
telemt_me_reconnect_success_total 13788
telemt_me_reader_eof_total 14872
telemt_me_idle_close_by_peer_total 14872
telemt_me_route_drop_no_conn_total 764036
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1891957
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9970
telemt_desync_full_logged_total 2698
telemt_desync_suppressed_total 7272
telemt_desync_frames_bucket_total{bucket="1_2"} 2478
telemt_desync_frames_bucket_total{bucket="3_10"} 3848
telemt_desync_frames_bucket_total{bucket="gt_10"} 3644
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14370
telemt_me_refill_failed_total 430
telemt_me_writer_restored_same_endpoint_total 13782
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 1890470
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 25432626532 (23.69 GB)
telemt_user_octets_to_client{user="hello"} 538653339292 (501.66 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86083.5 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776689
telemt_connections_bad_total 13167
telemt_handshake_timeouts_total 52507
telemt_upstream_connect_attempt_total 27594
telemt_upstream_connect_success_total 24645
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2522
telemt_me_reconnect_attempts_total 19466
telemt_me_reconnect_success_total 17380
telemt_me_reader_eof_total 18405
telemt_me_idle_close_by_peer_total 18402
telemt_me_route_drop_no_conn_total 304015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657721
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2829
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1933
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 922
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17635
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17357
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 660205
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 7012561738 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 186710705532 (173.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86083.2 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344403
telemt_connections_bad_total 8443
telemt_handshake_timeouts_total 121784
telemt_upstream_connect_attempt_total 22906
telemt_upstream_connect_success_total 22634
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33335
telemt_me_reconnect_success_total 17225
telemt_me_reader_eof_total 18517
telemt_me_idle_close_by_peer_total 18517
telemt_me_route_drop_no_conn_total 485177
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1163822
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3129
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 2208
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1184
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 17957
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17214
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 1163624
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 14026041465 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 347096307189 (323.26 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86083.9 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966065
telemt_connections_bad_total 77289
telemt_handshake_timeouts_total 91583
telemt_upstream_connect_attempt_total 23293
telemt_upstream_connect_success_total 23293
telemt_upstream_connect_attempts_per_request{bucket="1"} 23293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 952
telemt_me_reconnect_attempts_total 20067
telemt_me_reconnect_success_total 18995
telemt_me_reader_eof_total 20146
telemt_me_idle_close_by_peer_total 20145
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 313907
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770876
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 995
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19231
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18967
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 770219
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 9026841948 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 223691380748 (208.33 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86083.5 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060608
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 10135
telemt_upstream_connect_attempt_total 23287
telemt_upstream_connect_success_total 23187
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 23287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 990
telemt_me_reconnect_attempts_total 22835
telemt_me_reconnect_success_total 18761
telemt_me_reader_eof_total 19793
telemt_me_idle_close_by_peer_total 19793
telemt_me_route_drop_no_conn_total 376560
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963290
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3790
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 2396
telemt_desync_frames_bucket_total{bucket="1_2"} 1325
telemt_desync_frames_bucket_total{bucket="3_10"} 1429
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19129
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18761
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 963024
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 13887667635 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 339253062090 (315.95 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 117
```