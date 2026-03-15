# Server Metrics 2026-03-15 11:01:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 45990.5 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160012
telemt_connections_bad_total 70895
telemt_handshake_timeouts_total 9617
telemt_upstream_connect_attempt_total 9222
telemt_upstream_connect_success_total 9183
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9368
telemt_me_reconnect_success_total 6863
telemt_me_reader_eof_total 7320
telemt_me_idle_close_by_peer_total 7320
telemt_me_route_drop_no_conn_total 387608
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 979772
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3748
telemt_desync_full_logged_total 1052
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1468
telemt_desync_frames_bucket_total{bucket="gt_10"} 1359
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7041
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6852
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 979789
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 13875412516 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 393012397412 (366.02 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 45991.4 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456286
telemt_connections_bad_total 24710
telemt_handshake_timeouts_total 19926
telemt_upstream_connect_attempt_total 12173
telemt_upstream_connect_success_total 12109
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9525
telemt_me_reconnect_success_total 9464
telemt_me_reader_eof_total 10014
telemt_me_idle_close_by_peer_total 10014
telemt_me_route_drop_no_conn_total 116548
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360487
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1264
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9560
telemt_me_writer_restored_same_endpoint_total 9456
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 360770
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 5293123335 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 137621892308 (128.17 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 45991.3 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883925
telemt_connections_bad_total 29490
telemt_handshake_timeouts_total 85962
telemt_upstream_connect_attempt_total 10127
telemt_upstream_connect_success_total 10082
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7806
telemt_me_reconnect_success_total 7755
telemt_me_reader_eof_total 8210
telemt_me_idle_close_by_peer_total 8210
telemt_me_route_drop_no_conn_total 238147
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632316
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1524
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 986
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7857
telemt_me_writer_restored_same_endpoint_total 7736
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 631733
telemt_user_connections_current{user="hello"} 1174
telemt_user_octets_from_client{user="hello"} 9536435476 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 249667834324 (232.52 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 45991.2 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470463
telemt_connections_bad_total 58107
telemt_handshake_timeouts_total 26225
telemt_upstream_connect_attempt_total 13791
telemt_upstream_connect_success_total 13438
telemt_upstream_connect_fail_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 13791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 353
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31496
telemt_me_reconnect_success_total 11132
telemt_me_reader_eof_total 12096
telemt_me_idle_close_by_peer_total 12096
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 131868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11869
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 11100
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 353335
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 4149892148 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 110641362876 (103.04 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 45992.3 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486072
telemt_connections_bad_total 6155
telemt_handshake_timeouts_total 9247
telemt_upstream_connect_attempt_total 10177
telemt_upstream_connect_success_total 10126
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 7854
telemt_me_reconnect_success_total 7814
telemt_me_reader_eof_total 8300
telemt_me_idle_close_by_peer_total 8300
telemt_me_route_drop_no_conn_total 125925
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401070
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1569
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7902
telemt_me_writer_restored_same_endpoint_total 7806
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 401091
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 5035804144 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 150616561872 (140.27 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 126
```