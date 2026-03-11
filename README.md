# Server Metrics 2026-03-11 19:01:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102877.6 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2611981
telemt_connections_bad_total 48585
telemt_handshake_timeouts_total 57224
telemt_upstream_connect_attempt_total 21696
telemt_upstream_connect_success_total 21683
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5319
telemt_me_reconnect_attempts_total 34348
telemt_me_reconnect_success_total 16460
telemt_me_reader_eof_total 17800
telemt_me_idle_close_by_peer_total 17800
telemt_me_route_drop_no_conn_total 984465
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2388541
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12078
telemt_desync_full_logged_total 3344
telemt_desync_suppressed_total 8734
telemt_desync_frames_bucket_total{bucket="1_2"} 2967
telemt_desync_frames_bucket_total{bucket="3_10"} 4654
telemt_desync_frames_bucket_total{bucket="gt_10"} 4457
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17205
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16454
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 2386890
telemt_user_connections_current{user="hello"} 1154
telemt_user_octets_from_client{user="hello"} 35618643300 (33.17 GB)
telemt_user_octets_to_client{user="hello"} 677334058088 (630.82 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102934.2 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975356
telemt_connections_bad_total 16425
telemt_handshake_timeouts_total 87461
telemt_upstream_connect_attempt_total 31909
telemt_upstream_connect_success_total 28940
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 31909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2844
telemt_me_reconnect_attempts_total 22916
telemt_me_reconnect_success_total 20801
telemt_me_reader_eof_total 22021
telemt_me_idle_close_by_peer_total 22018
telemt_me_route_drop_no_conn_total 368521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813470
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3224
telemt_desync_full_logged_total 1045
telemt_desync_suppressed_total 2179
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21091
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20778
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 815917
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 9801381442 (9.13 GB)
telemt_user_octets_to_client{user="hello"} 235584463064 (219.41 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102934.0 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1677632
telemt_connections_bad_total 10484
telemt_handshake_timeouts_total 133433
telemt_upstream_connect_attempt_total 26694
telemt_upstream_connect_success_total 26358
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1974
telemt_me_reconnect_attempts_total 49726
telemt_me_reconnect_success_total 20071
telemt_me_reader_eof_total 21856
telemt_me_idle_close_by_peer_total 21856
telemt_me_route_drop_no_conn_total 611390
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1470113
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4073
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2880
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1545
telemt_desync_frames_bucket_total{bucket="gt_10"} 1582
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21276
telemt_me_refill_failed_total 921
telemt_me_writer_restored_same_endpoint_total 20059
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1205
telemt_user_connections_total{user="hello"} 1469780
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 19031737293 (17.72 GB)
telemt_user_octets_to_client{user="hello"} 447204638577 (416.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102934.5 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1198357
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 110430
telemt_upstream_connect_attempt_total 27777
telemt_upstream_connect_success_total 27777
telemt_upstream_connect_attempts_per_request{bucket="1"} 27777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1421
telemt_me_reconnect_attempts_total 27227
telemt_me_reconnect_success_total 22616
telemt_me_reader_eof_total 24007
telemt_me_idle_close_by_peer_total 24006
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 400024
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974979
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2042
telemt_desync_full_logged_total 780
telemt_desync_suppressed_total 1262
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 23000
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22583
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 974240
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 11597314508 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 295887232328 (275.57 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7610.5 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123340
telemt_connections_bad_total 628
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 2156
telemt_upstream_connect_success_total 2155
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1732
telemt_me_reconnect_success_total 1713
telemt_me_reader_eof_total 1748
telemt_me_idle_close_by_peer_total 1748
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 42677
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 230
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1736
telemt_me_writer_restored_same_endpoint_total 1689
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 113623
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 6502996916 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 38895730764 (36.22 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 81
```