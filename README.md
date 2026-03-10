# Server Metrics 2026-03-10 20:16:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20978.8 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628372
telemt_connections_bad_total 8007
telemt_handshake_timeouts_total 6464
telemt_upstream_connect_attempt_total 4390
telemt_upstream_connect_success_total 4381
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 333
telemt_me_reconnect_attempts_total 14889
telemt_me_reconnect_success_total 3239
telemt_me_reader_eof_total 3626
telemt_me_idle_close_by_peer_total 3626
telemt_me_route_drop_no_conn_total 263353
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593006
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3098
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 2261
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1170
telemt_desync_frames_bucket_total{bucket="gt_10"} 1064
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3622
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3233
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 592828
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 8506422040 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 176713558628 (164.58 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21035.6 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274283
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16790
telemt_upstream_connect_attempt_total 10126
telemt_upstream_connect_success_total 7280
telemt_upstream_connect_fail_total 2846
telemt_upstream_connect_attempts_per_request{bucket="1"} 10126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2846
telemt_me_keepalive_timeout_total 734
telemt_me_reconnect_attempts_total 4684
telemt_me_reconnect_success_total 3891
telemt_me_reader_eof_total 4071
telemt_me_idle_close_by_peer_total 4069
telemt_me_route_drop_no_conn_total 154012
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232986
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1231
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3967
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3870
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 234580
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 2405808714 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 56015583150 (52.17 GB)
telemt_user_msgs_from_client{user="hello"} 5762
telemt_user_msgs_to_client{user="hello"} 6647
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21035.5 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449049
telemt_connections_bad_total 2074
telemt_handshake_timeouts_total 32451
telemt_upstream_connect_attempt_total 6398
telemt_upstream_connect_success_total 6302
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 11100
telemt_me_reconnect_success_total 4126
telemt_me_reader_eof_total 4466
telemt_me_idle_close_by_peer_total 4466
telemt_me_route_drop_no_conn_total 155172
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388891
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 955
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4418
telemt_me_refill_failed_total 216
telemt_me_writer_restored_same_endpoint_total 4115
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 389836
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 5610886849 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 120823106969 (112.53 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21036.0 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302644
telemt_connections_bad_total 20697
telemt_handshake_timeouts_total 26268
telemt_upstream_connect_attempt_total 5784
telemt_upstream_connect_success_total 5784
telemt_upstream_connect_attempts_per_request{bucket="1"} 5784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 5694
telemt_me_reconnect_success_total 4677
telemt_me_reader_eof_total 4901
telemt_me_idle_close_by_peer_total 4901
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 98586
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243957
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 392
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4755
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4664
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 243658
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 3730482520 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 75456582784 (70.27 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21035.6 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318380
telemt_connections_bad_total 923
telemt_handshake_timeouts_total 2032
telemt_upstream_connect_attempt_total 6720
telemt_upstream_connect_success_total 6693
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 7966
telemt_me_reconnect_success_total 5559
telemt_me_reader_eof_total 5778
telemt_me_idle_close_by_peer_total 5778
telemt_me_route_drop_no_conn_total 116330
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299876
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1717
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5716
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 5559
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 299787
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 5773714844 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 99676755756 (92.83 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 51
```