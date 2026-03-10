# Server Metrics 2026-03-10 23:04:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31058.4 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751637
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8426
telemt_upstream_connect_attempt_total 6699
telemt_upstream_connect_success_total 6690
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 16719
telemt_me_reconnect_success_total 5058
telemt_me_reader_eof_total 5571
telemt_me_idle_close_by_peer_total 5571
telemt_me_route_drop_no_conn_total 311998
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711233
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3483
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5462
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5052
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 711022
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 10082472824 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 214130342196 (199.42 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31115.2 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325885
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17592
telemt_upstream_connect_attempt_total 13444
telemt_upstream_connect_success_total 10574
telemt_upstream_connect_fail_total 2870
telemt_upstream_connect_attempts_per_request{bucket="1"} 13444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2870
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 6836
telemt_me_reconnect_success_total 6027
telemt_me_reader_eof_total 6337
telemt_me_idle_close_by_peer_total 6335
telemt_me_route_drop_no_conn_total 168768
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275744
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1677
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1214
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6118
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6006
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 278013
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2720037566 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 65371540232 (60.88 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31115.1 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538575
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 33927
telemt_upstream_connect_attempt_total 8505
telemt_upstream_connect_success_total 8383
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 16768
telemt_me_reconnect_success_total 5712
telemt_me_reader_eof_total 6274
telemt_me_idle_close_by_peer_total 6274
telemt_me_route_drop_no_conn_total 186267
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472796
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6144
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5701
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 473728
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 6699941373 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 150241128997 (139.92 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31115.4 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383364
telemt_connections_bad_total 29857
telemt_handshake_timeouts_total 34727
telemt_upstream_connect_attempt_total 8665
telemt_upstream_connect_success_total 8665
telemt_upstream_connect_attempts_per_request{bucket="1"} 8665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 8093
telemt_me_reconnect_success_total 7067
telemt_me_reader_eof_total 7440
telemt_me_idle_close_by_peer_total 7440
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 121649
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305847
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7173
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7053
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 305522
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 4076017328 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 88018224128 (81.97 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31115.0 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404984
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 2640
telemt_upstream_connect_attempt_total 9590
telemt_upstream_connect_success_total 9551
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 11678
telemt_me_reconnect_success_total 7918
telemt_me_reader_eof_total 8307
telemt_me_idle_close_by_peer_total 8307
telemt_me_route_drop_no_conn_total 139713
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376039
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2188
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 1347
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8144
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7918
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 375847
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 6460424116 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 140067786000 (130.45 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 36
```