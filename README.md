# Server Metrics 2026-03-15 17:54:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 70820.7 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2502369
telemt_connections_bad_total 149793
telemt_handshake_timeouts_total 32694
telemt_upstream_connect_attempt_total 13735
telemt_upstream_connect_success_total 13676
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15035
telemt_me_reconnect_success_total 10137
telemt_me_reader_eof_total 10835
telemt_me_idle_close_by_peer_total 10835
telemt_me_route_drop_no_conn_total 864639
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2089351
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8105
telemt_desync_full_logged_total 2203
telemt_desync_suppressed_total 5902
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 3104
telemt_desync_frames_bucket_total{bucket="gt_10"} 3018
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10461
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10126
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2088830
telemt_user_connections_current{user="hello"} 2331
telemt_user_octets_from_client{user="hello"} 31238289112 (29.09 GB)
telemt_user_octets_to_client{user="hello"} 794787263132 (740.20 GB)
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 70821.5 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969713
telemt_connections_bad_total 54586
telemt_handshake_timeouts_total 62870
telemt_upstream_connect_attempt_total 17665
telemt_upstream_connect_success_total 17570
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14881
telemt_me_reconnect_success_total 13671
telemt_me_reader_eof_total 14464
telemt_me_idle_close_by_peer_total 14464
telemt_me_route_drop_no_conn_total 250753
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748697
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2205
telemt_desync_full_logged_total 744
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 831
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13887
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13659
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 748928
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 10907957143 (10.16 GB)
telemt_user_octets_to_client{user="hello"} 281016174876 (261.72 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 70821.5 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2144635
telemt_connections_bad_total 50409
telemt_handshake_timeouts_total 214661
telemt_upstream_connect_attempt_total 15262
telemt_upstream_connect_success_total 15186
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12886
telemt_me_reconnect_success_total 11616
telemt_me_reader_eof_total 12309
telemt_me_idle_close_by_peer_total 12309
telemt_me_route_drop_no_conn_total 555907
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1333266
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3437
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 2197
telemt_desync_frames_bucket_total{bucket="1_2"} 779
telemt_desync_frames_bucket_total{bucket="3_10"} 1341
telemt_desync_frames_bucket_total{bucket="gt_10"} 1317
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11822
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11597
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 1329157
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 24699695196 (23.00 GB)
telemt_user_octets_to_client{user="hello"} 490222509968 (456.56 GB)
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 70821.5 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034141
telemt_connections_bad_total 82050
telemt_handshake_timeouts_total 50511
telemt_upstream_connect_attempt_total 170612
telemt_upstream_connect_success_total 170025
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 170612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61579
telemt_me_reconnect_success_total 13515
telemt_me_reader_eof_total 15381
telemt_me_idle_close_by_peer_total 15381
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 244132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650730
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1827
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15161
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13479
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 803246
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 15036129169 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 286134543576 (266.48 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 70822.3 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1047480
telemt_connections_bad_total 12565
telemt_handshake_timeouts_total 23206
telemt_upstream_connect_attempt_total 15572
telemt_upstream_connect_success_total 15489
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15635
telemt_me_reconnect_success_total 11940
telemt_me_reader_eof_total 12735
telemt_me_idle_close_by_peer_total 12735
telemt_me_route_drop_no_conn_total 261076
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867600
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2946
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 1957
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1094
telemt_desync_frames_bucket_total{bucket="gt_10"} 950
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12199
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11932
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 867624
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 10861427880 (10.12 GB)
telemt_user_octets_to_client{user="hello"} 305248908196 (284.29 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 119
```