# Server Metrics 2026-03-11 00:46:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37152.8 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793506
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9044
telemt_upstream_connect_attempt_total 8105
telemt_upstream_connect_success_total 8096
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 17823
telemt_me_reconnect_success_total 6158
telemt_me_reader_eof_total 6755
telemt_me_idle_close_by_peer_total 6755
telemt_me_route_drop_no_conn_total 326674
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751215
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3557
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 2562
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6573
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6152
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 750992
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 10452599328 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 224792873300 (209.35 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37209.5 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342524
telemt_connections_bad_total 2389
telemt_handshake_timeouts_total 17651
telemt_upstream_connect_attempt_total 15159
telemt_upstream_connect_success_total 12279
telemt_upstream_connect_fail_total 2880
telemt_upstream_connect_attempts_per_request{bucket="1"} 15159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2880
telemt_me_keepalive_timeout_total 1706
telemt_me_reconnect_attempts_total 8240
telemt_me_reconnect_success_total 7426
telemt_me_reader_eof_total 7838
telemt_me_idle_close_by_peer_total 7836
telemt_me_route_drop_no_conn_total 172779
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291913
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1763
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 1264
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7527
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7405
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 294182
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2840354174 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70337475332 (65.51 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37209.3 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569469
telemt_connections_bad_total 4053
telemt_handshake_timeouts_total 34118
telemt_upstream_connect_attempt_total 10231
telemt_upstream_connect_success_total 10088
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 10231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 509
telemt_me_reconnect_attempts_total 18169
telemt_me_reconnect_success_total 7108
telemt_me_reader_eof_total 7758
telemt_me_idle_close_by_peer_total 7758
telemt_me_route_drop_no_conn_total 195388
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502747
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7551
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7097
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 503671
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 6825334097 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 154582628653 (143.97 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37209.8 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416490
telemt_connections_bad_total 35411
telemt_handshake_timeouts_total 39116
telemt_upstream_connect_attempt_total 10632
telemt_upstream_connect_success_total 10632
telemt_upstream_connect_attempts_per_request{bucket="1"} 10632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 9758
telemt_me_reconnect_success_total 8726
telemt_me_reader_eof_total 9229
telemt_me_idle_close_by_peer_total 9229
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 128057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328939
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 716
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 8843
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8710
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 328615
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 4203796432 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 90733287996 (84.50 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37209.4 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440738
telemt_connections_bad_total 4404
telemt_handshake_timeouts_total 2770
telemt_upstream_connect_attempt_total 11244
telemt_upstream_connect_success_total 11197
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 13023
telemt_me_reconnect_success_total 9256
telemt_me_reader_eof_total 9737
telemt_me_idle_close_by_peer_total 9737
telemt_me_route_drop_no_conn_total 147131
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405946
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2270
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9492
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9256
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 405675
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 8355461160 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 146132366896 (136.10 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```