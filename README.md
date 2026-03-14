# Server Metrics 2026-03-14 06:35:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 174982.4 (48h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4926786
telemt_connections_bad_total 40200
telemt_handshake_timeouts_total 112825
telemt_upstream_connect_attempt_total 36766
telemt_upstream_connect_success_total 36527
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 36766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 7324
telemt_me_reconnect_attempts_total 35634
telemt_me_reconnect_success_total 25484
telemt_me_reader_eof_total 27351
telemt_me_idle_close_by_peer_total 27350
telemt_me_route_drop_no_conn_total 1866412
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4521798
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17359
telemt_desync_full_logged_total 4697
telemt_desync_suppressed_total 12662
telemt_desync_frames_bucket_total{bucket="1_2"} 4332
telemt_desync_frames_bucket_total{bucket="3_10"} 6616
telemt_desync_frames_bucket_total{bucket="gt_10"} 6411
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 26166
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25471
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 4523302
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 66233764460 (61.69 GB)
telemt_user_octets_to_client{user="hello"} 1425703358941 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74646.3 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812620
telemt_connections_bad_total 53807
telemt_handshake_timeouts_total 14876
telemt_upstream_connect_attempt_total 20245
telemt_upstream_connect_success_total 19974
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2142
telemt_me_reconnect_attempts_total 17706
telemt_me_reconnect_success_total 14242
telemt_me_reader_eof_total 15133
telemt_me_idle_close_by_peer_total 15132
telemt_me_route_drop_no_conn_total 266296
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645225
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1875
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1307
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14553
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14234
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 647141
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 6793097485 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 217766606024 (202.81 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 204603.2 (56h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3538650
telemt_connections_bad_total 40317
telemt_handshake_timeouts_total 232658
telemt_upstream_connect_attempt_total 46273
telemt_upstream_connect_success_total 46252
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10664
telemt_me_reconnect_attempts_total 40729
telemt_me_reconnect_success_total 35754
telemt_me_reader_eof_total 37981
telemt_me_idle_close_by_peer_total 37980
telemt_me_route_drop_no_conn_total 1210875
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2951309
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9748
telemt_desync_full_logged_total 3269
telemt_desync_suppressed_total 6479
telemt_desync_frames_bucket_total{bucket="1_2"} 1698
telemt_desync_frames_bucket_total{bucket="3_10"} 3519
telemt_desync_frames_bucket_total{bucket="gt_10"} 4531
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 36251
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35713
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 2950461
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 48945414148 (45.58 GB)
telemt_user_octets_to_client{user="hello"} 1055159140541 (982.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 204605.6 (56h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2363092
telemt_connections_bad_total 23292
telemt_handshake_timeouts_total 278390
telemt_upstream_connect_attempt_total 63786
telemt_upstream_connect_success_total 61297
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63512
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20511
telemt_me_reconnect_attempts_total 53135
telemt_me_reconnect_success_total 44089
telemt_me_reader_eof_total 47273
telemt_me_idle_close_by_peer_total 47266
telemt_me_route_drop_no_conn_total 796971
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1864957
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3903
telemt_desync_full_logged_total 1264
telemt_desync_suppressed_total 2639
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 44754
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44065
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 1870998
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 28233694583 (26.29 GB)
telemt_user_octets_to_client{user="hello"} 688890219522 (641.58 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74039.1 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 785895
telemt_connections_bad_total 8102
telemt_handshake_timeouts_total 9240
telemt_upstream_connect_attempt_total 18878
telemt_upstream_connect_success_total 18370
telemt_upstream_connect_fail_total 508
telemt_upstream_connect_attempts_per_request{bucket="1"} 18878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 508
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 59970
telemt_me_reconnect_success_total 14665
telemt_me_reader_eof_total 16444
telemt_me_idle_close_by_peer_total 16443
telemt_me_route_drop_no_conn_total 302807
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734060
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1779
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 561
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16206
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14660
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 733921
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 13015415544 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 246776481480 (229.83 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 70
```