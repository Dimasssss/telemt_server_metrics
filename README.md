# Server Metrics 2026-03-11 09:29:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68566.9 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1461533
telemt_connections_bad_total 19588
telemt_handshake_timeouts_total 40607
telemt_upstream_connect_attempt_total 14298
telemt_upstream_connect_success_total 14289
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 779
telemt_me_reconnect_attempts_total 22497
telemt_me_reconnect_success_total 10809
telemt_me_reader_eof_total 11714
telemt_me_idle_close_by_peer_total 11714
telemt_me_route_drop_no_conn_total 539053
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326533
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6500
telemt_desync_full_logged_total 1800
telemt_desync_suppressed_total 4700
telemt_desync_frames_bucket_total{bucket="1_2"} 1715
telemt_desync_frames_bucket_total{bucket="3_10"} 2472
telemt_desync_frames_bucket_total{bucket="gt_10"} 2313
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11278
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10803
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 1325063
telemt_user_connections_current{user="hello"} 1231
telemt_user_octets_from_client{user="hello"} 17451022260 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 381369236164 (355.18 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68623.6 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561120
telemt_connections_bad_total 9672
telemt_handshake_timeouts_total 30702
telemt_upstream_connect_attempt_total 23249
telemt_upstream_connect_success_total 20320
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2098
telemt_me_reconnect_attempts_total 14761
telemt_me_reconnect_success_total 13923
telemt_me_reader_eof_total 14744
telemt_me_idle_close_by_peer_total 14742
telemt_me_route_drop_no_conn_total 234670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476016
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2204
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 678
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14086
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13901
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 478253
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 4657169370 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 130262504448 (121.32 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68623.4 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979652
telemt_connections_bad_total 7500
telemt_handshake_timeouts_total 96986
telemt_upstream_connect_attempt_total 18610
telemt_upstream_connect_success_total 18383
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 26220
telemt_me_reconnect_success_total 13854
telemt_me_reader_eof_total 14890
telemt_me_idle_close_by_peer_total 14890
telemt_me_route_drop_no_conn_total 320955
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836647
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2380
telemt_desync_full_logged_total 707
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 575
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 937
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14422
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13843
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 837522
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 9928339701 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 254961317441 (237.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68623.9 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714767
telemt_connections_bad_total 64457
telemt_handshake_timeouts_total 69299
telemt_upstream_connect_attempt_total 18918
telemt_upstream_connect_success_total 18918
telemt_upstream_connect_attempts_per_request{bucket="1"} 18918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 707
telemt_me_reconnect_attempts_total 16530
telemt_me_reconnect_success_total 15476
telemt_me_reader_eof_total 16439
telemt_me_idle_close_by_peer_total 16438
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 223444
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559105
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1257
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15658
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15453
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 558479
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 6524527592 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 158426577336 (147.55 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68623.5 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757844
telemt_connections_bad_total 5983
telemt_handshake_timeouts_total 7195
telemt_upstream_connect_attempt_total 18640
telemt_upstream_connect_success_total 18566
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 766
telemt_me_reconnect_attempts_total 18798
telemt_me_reconnect_success_total 15006
telemt_me_reader_eof_total 15864
telemt_me_idle_close_by_peer_total 15864
telemt_me_route_drop_no_conn_total 259400
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686532
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2921
telemt_desync_full_logged_total 1107
telemt_desync_suppressed_total 1814
telemt_desync_frames_bucket_total{bucket="1_2"} 1023
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 699
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15316
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15006
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 686216
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 10882074599 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 246971283682 (230.01 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 99
```