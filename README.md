# Server Metrics 2026-03-14 10:40:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 189721.7 (52h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5449856
telemt_connections_bad_total 56090
telemt_handshake_timeouts_total 120289
telemt_upstream_connect_attempt_total 39869
telemt_upstream_connect_success_total 39613
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7621
telemt_me_reconnect_attempts_total 41565
telemt_me_reconnect_success_total 27851
telemt_me_reader_eof_total 29920
telemt_me_idle_close_by_peer_total 29919
telemt_me_route_drop_no_conn_total 2060248
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4995400
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19053
telemt_desync_full_logged_total 5224
telemt_desync_suppressed_total 13829
telemt_desync_frames_bucket_total{bucket="1_2"} 4664
telemt_desync_frames_bucket_total{bucket="3_10"} 7259
telemt_desync_frames_bucket_total{bucket="gt_10"} 7130
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28685
telemt_me_refill_failed_total 423
telemt_me_writer_restored_same_endpoint_total 27838
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 834
telemt_user_connections_total{user="hello"} 4996856
telemt_user_connections_current{user="hello"} 1748
telemt_user_octets_from_client{user="hello"} 76621308772 (71.36 GB)
telemt_user_octets_to_client{user="hello"} 1590100782493 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89385.5 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1011287
telemt_connections_bad_total 58117
telemt_handshake_timeouts_total 22253
telemt_upstream_connect_attempt_total 23510
telemt_upstream_connect_success_total 23216
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2283
telemt_me_reconnect_attempts_total 26601
telemt_me_reconnect_success_total 16724
telemt_me_reader_eof_total 17915
telemt_me_idle_close_by_peer_total 17914
telemt_me_route_drop_no_conn_total 340147
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826277
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2306
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1582
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17269
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16716
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 828178
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 9000321933 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 290375065756 (270.43 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 219342.1 (60h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3871925
telemt_connections_bad_total 45759
telemt_handshake_timeouts_total 256653
telemt_upstream_connect_attempt_total 49534
telemt_upstream_connect_success_total 49513
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11031
telemt_me_reconnect_attempts_total 44274
telemt_me_reconnect_success_total 38281
telemt_me_reader_eof_total 40657
telemt_me_idle_close_by_peer_total 40656
telemt_me_route_drop_no_conn_total 1329654
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3236967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10364
telemt_desync_full_logged_total 3524
telemt_desync_suppressed_total 6840
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 3749
telemt_desync_frames_bucket_total{bucket="gt_10"} 4739
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38848
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38240
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 3236106
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 54757460332 (51.00 GB)
telemt_user_octets_to_client{user="hello"} 1160160563669 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 219344.6 (60h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2551159
telemt_connections_bad_total 23425
telemt_handshake_timeouts_total 323448
telemt_upstream_connect_attempt_total 67889
telemt_upstream_connect_success_total 65384
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67615
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20756
telemt_me_reconnect_attempts_total 59104
telemt_me_reconnect_success_total 47446
telemt_me_reader_eof_total 50832
telemt_me_idle_close_by_peer_total 50824
telemt_me_route_drop_no_conn_total 850158
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1997445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4049
telemt_desync_full_logged_total 1325
telemt_desync_suppressed_total 2724
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48222
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47422
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 2003662
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 29813126159 (27.77 GB)
telemt_user_octets_to_client{user="hello"} 720786566558 (671.28 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88778.2 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998215
telemt_connections_bad_total 16996
telemt_handshake_timeouts_total 13073
telemt_upstream_connect_attempt_total 22186
telemt_upstream_connect_success_total 21592
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 22186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 1710
telemt_me_reconnect_attempts_total 75355
telemt_me_reconnect_success_total 17166
telemt_me_reader_eof_total 19394
telemt_me_idle_close_by_peer_total 19393
telemt_me_route_drop_no_conn_total 386788
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923908
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2517
telemt_desync_full_logged_total 782
telemt_desync_suppressed_total 1735
telemt_desync_frames_bucket_total{bucket="1_2"} 855
telemt_desync_frames_bucket_total{bucket="3_10"} 926
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19142
telemt_me_refill_failed_total 1813
telemt_me_writer_restored_same_endpoint_total 17161
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1976
telemt_user_connections_total{user="hello"} 923846
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 16487325168 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 309296172636 (288.05 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 84
```